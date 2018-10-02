# PowerShellCommands
List of useful PowerShell Commands

**Get list of running applications**
```powershell
gps | ? {$_.mainwindowhandle -ne 0} | select-object name, mainwindowtitle
```
