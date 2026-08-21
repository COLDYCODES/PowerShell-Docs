Now:
```
Get-Process | Sort-Object CPU -Descending
```
This sorts processes by CPU usage.

Want only the first 10?
```
Get-Process | Sort-Object CPU -Descending | Select-Object -First 10
```
Look at what we just built:
```
Get-Process
    ↓
Sort-Object
    ↓
Select-Object
```
That's the PowerShell pipeline.
