Now let's say you have 200 processes.
You only want using more than 100 MB of memory.
Try:
```
Get-Process | Where-Object WorkingSet -gt 100MB
```
That's:
```
Get processes
      ↓
Where the WorkingSet is greater than 100MB
```
You just performed object-based filtering.
