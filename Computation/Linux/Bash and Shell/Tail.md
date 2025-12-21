#computation #linux #shell 

## Default Behavior

The `tail` command in Linux **by default** displays the last 10 lines of a file.

### Basic Usage
```bash
tail [file]
```

| Flag | Function                                         | Example             |
| ---- | ------------------------------------------------ | ------------------- |
| -n   | Specifies the number of lines to display         | `$ tail -n 20 file` |
| -c   | Specifies the number of bytes (i.e., characters) | `$ tail -c 5 file`  |
| -f   | Monitors a file in real-time                     | `$ tail -f file`    |
