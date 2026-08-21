```
Get-Process | Select-Object Name, Id
```
The `|` is the pipeline.

Read it like:
> Get process and send them to Select-Object.
The output of the command becomes the input of the next.
