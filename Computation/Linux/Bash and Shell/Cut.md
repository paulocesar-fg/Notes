#computation #linux #shell 

## Definition

The `cut` command in Linux is used to **extract specific parts** of each line of a text file, such as columns, fields, or characters.

### Basic Syntax
```bash
cut [options] [file]
```

### Common Options

| Flag               | Function                                                                                   | Example                          |
| ------------------ | ------------------------------------------------------------------------------------------ | -------------------------------- |
| -d                 | Specifies the delimiter character                                                          | `$ cut -d ':' -f 1 file`         |
| -f                 | Selects specific fields (columns)                                                          | `$ cut -d ',' -f 2,3 file`       |
| -c                 | Selects specific character positions                                                       | `$ cut -c 1-5 file`              |
| ```--complement``` | Complement the selection (select everything **except** the specified fields or characters) | `$ cut -c 1-5 --complement file` |


