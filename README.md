<div align="center">

## helpful sleep API call to suspend actions


</div>

### Description

What this API call does is suspend ALL actions for a certain amount of milliseconds(1000 milliseconds=1 second)(duh...)
 
### More Info
 
Just dont enter a number that is huge, or else you will be waiting for a very long time

Dont enter a super large number.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Derek Haas](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/derek-haas.md)
**Level**          |Unknown
**User Rating**    |4.2 (164 globes from 39 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Windows API Call/ Explanation](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/windows-api-call-explanation__1-39.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/derek-haas-helpful-sleep-api-call-to-suspend-actions__1-2771/archive/master.zip)

### API Declarations

```
Public Declare Sub Sleep Lib "kernel32" (ByVal dwMilliseconds As Long)
```


### Source Code

```
Private Sub Form_Load()
Call Sleep(1000)
End Sub
'This code example will "sleep" for 1 second, and then load the form.
```

