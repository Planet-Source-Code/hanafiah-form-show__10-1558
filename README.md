<div align="center">

## Form Show


</div>

### Description

vb6 Form.show method in vb.net
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Hanafiah](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/hanafiah.md)
**Level**          |Beginner
**User Rating**    |3.0 (24 globes from 8 users)
**Compatibility**  |VB\.NET
**Category**       |[Debugging and Error Handling](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/debugging-and-error-handling__10-6.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/hanafiah-form-show__10-1558/archive/master.zip)





### Source Code

I'm beginner in VB.Net, just to share some tips
Let says you have 2 form, Form_1 and Form_2. Inside Form_1 you have 1 command button called command_1. if you show Form_2 when press command_1. in VB6 just can use <br><br>
Form_2.show<br><br>
But how to do it in vb.net?<br>
Private Sub command_1_Click(ByVal Sender As Object, ByVal e as EventArgs) Handles command_1.Click <br>
Dim frm As New Form_2() <br>
frm.Show()<br>
End Sub<br>
<br>
<br>
but if you don't need to show new form2 every time you press command_1. just put your declaration outside your sub. like this<br><br>
Dim frm As New Form_2() <br>
Private Sub command_1_Click(ByVal Sender As Object, ByVal e as EventArgs) Handles command_1.Click <br>
frm.Show()<br>
End Sub<br>

