# Challenge 1
> Create a command that:
> Shows the 5 processes using the most CPU.
```
Get-Process | Sort-Object -First 5
