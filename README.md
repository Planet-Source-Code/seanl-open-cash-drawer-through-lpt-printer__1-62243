<div align="center">

## Open Cash Drawer Through LPT Printer


</div>

### Description

This code opens a cash drawer that is connected through a printer using a connector that goes from a reciept printer to an electronic cash drawer. This will kick the drawer open. This should work on an epson printer connected to a cash drawer.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[SeanL](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/seanl.md)
**Level**          |Intermediate
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) , VBA MS Access, VBA MS Excel
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/seanl-open-cash-drawer-through-lpt-printer__1-62243/archive/master.zip)





### Source Code

```
Open "LPT1" For Output As #1
Print #1, Chr$(27); Chr$(112); Chr$(0)
Close #1
'Short and simple :)
```

