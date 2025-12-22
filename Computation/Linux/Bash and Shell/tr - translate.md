#computation #linux #shell 

## Definition

The translate (tr) command is a utility in Linux that translates or delete characters from standard input(stdin)

#### Syntax:
```bash 
$ tr [Options] [SET1] [SET2]
```

## Options

| Option | Function                                                                              |
| ------ | ------------------------------------------------------------------------------------- |
| -c     | **Applies** operation to characters **not in** the specified set.                     |
| -d     | **Deletes** all characters in the first set from the output.                          |
| -s     | **Replaces** repeated occurrences of characters in set1 with a **single** occurrence. |
| -t     | **Truncates** SET1 to match the length of SET2 during translation.                    |

## Common Classes

| Class      | Function                                                                 |
| ---------- | ------------------------------------------------------------------------ |
| [:alnum:]  | all letters and digits                                                   |
| [:alpha:]  | all letters                                                              |
| [:blank:]  | all horizontal whitespaces characters(space and tabs)                    |
| [:cntrl:]  | all control characters                                                   |
| [:digit:]  | all digits (0-9)                                                         |
| [:graph:]  | all printable characters not including space                             |
| [:lower:]  | all lowercase letters [a-z]                                              |
| [:upper:]  | all uppercase letters [A-Z]                                              |
| [:space:]  | all horizontal and vertical whitespaces characters (space, tab, newline) |
| [:xdigit:] | all hexadecimal digits                                                   |
