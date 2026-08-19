Run:
```
Get-Process
Get-Process | Get-Member
```

**What Happened?**
`Get-Member` tells you what kind of objects are coming through the pipeline and what they contain.

Properties Ex:
```
Name
Id
CPU
Path
PriorityClass
WorkingSet
```

Methods Ex:
```
Kill()
CloseMainWindow()
WaitForExit()
```

Important Idea:
```
Get-Process
     ↓
Process objects
     ↓
Get-Member
     ↓
"What do these objects contain?"
```
