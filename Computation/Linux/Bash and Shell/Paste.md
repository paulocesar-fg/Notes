#computation #linux #shell 

## Definition

The `paste` command in Linux is used to **merge lines of files** side by side, separated by a delimiter (default is a tab).

### Basic Syntax
```bash
paste [options] [file1] [file2] ...
```

### Common Options

| Flag | Function                                         | Example                     |
| ---- | ----------------------------------------------- | --------------------------- |
| -d   | Specifies a delimiter to separate columns       | `$ paste -d ',' file1 file2` |
| -s   | Paste one file at a time (serial)               | `$ paste -s file1`           |
| -z   | Treat consecutive delimiters as a single one    | `$ paste -z file1 file2`     |
