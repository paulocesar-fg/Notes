#computation #linux #shell 

## Definition

The `expand` command in Linux is used to **convert tabs to spaces** in a text file.

### Basic Syntax
```bash
expand [options] [file]
```

### Common Options

| Flag | Function                                           | Example                 |
| ---- | ------------------------------------------------- | ----------------------- |
| -t   | Specify the number of spaces per tab (default is 8) | `$ expand -t 4 file`    |
| -i   | Ignore tabs in leading whitespace                 | `$ expand -i file`      |
