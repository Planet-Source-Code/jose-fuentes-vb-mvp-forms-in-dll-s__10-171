<div align="center">

## Forms in DLL's


</div>

### Description

Have you ever wanted to build UI components to be used everywhere well you can build them in a DLL and use them everywhere.

"note this was possible without tricks in vb6"
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jose Fuentes VB MVP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jose-fuentes-vb-mvp.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jose-fuentes-vb-mvp-forms-in-dll-s__10-171/archive/master.zip)





### Source Code

```
Ok it's pretty simple if you want to make a DLL that has a form or even more then one form on it then do this.
first open a new windowforms project
name it and hit ok
ok now on the project name in the solution builder listing the files right click and hit properties.
Go to the output type dropdown and select class libaray and boom you are done now comple it and then bring it in as a reference into your exe project and you can now use the forms in the dll
dim hi as new testdll.form1
hi.show()
boom your done.
now for debuging your forms in the dll you can build a windowsforms app exe that uses the dll and then in the DLL project going to the same right click and properites of the project you will find configuatjion properties and under debuging you can set it to run an external application just set that on your test.exe that uses the dll and boom you are ready to debug.
FYI if you make a change in the dll you will need to recompile the test.exe before going into debug again.
Hope this helps
```

