#computation #linux #shell 


## Default Behavior

The `head` command in Linux **by default** displays the first 10 lines of a file.

#### Basic Usage:
```bash
head [file]
```

| Flag | Function                                         | Example             |
| ---- | ------------------------------------------------ | ------------------- |
| -n   | Specifies the number of lines to display         | `$ head -n 20 file` |
| -c   | Specifies the number of bytes (i.e., characters) | `$ head -c 5 file`  |
