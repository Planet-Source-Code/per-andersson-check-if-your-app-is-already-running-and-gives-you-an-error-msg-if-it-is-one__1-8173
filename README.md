<div align="center">

## Check if your app is already running and gives you an error msg if it is\. One line of code \*Updated\*


</div>

### Description

Check if your app is running, if it is the program will show an error message. You can also visit www.FireStorm.Now.Nu
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Per Andersson](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/per-andersson.md)
**Level**          |Beginner
**User Rating**    |3.1 (25 globes from 8 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/per-andersson-check-if-your-app-is-already-running-and-gives-you-an-error-msg-if-it-is-one__1-8173/archive/master.zip)

### API Declarations

www.FireStorm.Now.Nu


### Source Code

```
Private Sub Form_Load()
If App.PrevInstance = True Then MsgBox "This app is already running":End
End Sub
```

