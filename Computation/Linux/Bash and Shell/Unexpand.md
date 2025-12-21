#computation #linux #shell 

## Definition

The `unexpand` command in Linux is used to **convert spaces to tabs** in a text file.

### Basic Syntax
```bash
unexpand [options] [file]
```

### Common Options

| Flag | Function                                                          | Example                |
| ---- | ----------------------------------------------------------------- | ---------------------- |
| -t   | Specify the number of spaces to convert into a tab (default is 8) | `$ unexpand -t 4 file` |
| -a   | Convert all sequences of spaces, not just leading ones            | `$ unexpand -a file`   |
|      |                                                                   |                        |
