<div align="center">

## Accept only numbers in a text box control with one line of code \* MUST SEE\*


</div>

### Description

first, my apologies for my bad english, hehe.

this example demonstrates how to accept only numbers in a textbox control with ONE LINE OF CODE AND FAST CODE. * MUST SEE *
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Marco Antonio Alves](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/marco-antonio-alves.md)
**Level**          |Beginner
**User Rating**    |3.8 (49 globes from 13 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/marco-antonio-alves-accept-only-numbers-in-a-text-box-control-with-one-line-of-code-must-s__1-27869/archive/master.zip)





### Source Code

```
on keypress event of textbox type code bellow:
KeyAscii = IIf(Not KeyAscii = 8 And Not Val((Chr(KeyAscii))) > 0, 0, KeyAscii)
```

