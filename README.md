## Usage

`./truthtable col1=false:true,col2=READY:PAUSED:PLAYING`

will produce

```
| col1    | col2    |
|---------|---------|
| false   | READY   |
| true    | READY   |
| false   | PAUSED  |
| true    | PAUSED  |
| false   | PLAYING |
| true    | PLAYING |
```
