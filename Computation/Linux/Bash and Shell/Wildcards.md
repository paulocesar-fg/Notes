#computation #linux #shell 

## Definition

In Linux, **wildcards** (also called **globs**) are special characters used to **match filenames or patterns** in the shell.

### Common Wildcards

| Wildcard | Function                                              | Example                                                        |
| -------- | ----------------------------------------------------- | -------------------------------------------------------------- |
| `*`      | Matches **any number of characters** (including none) | `$ ls *.txt` → lists all `.txt` files                          |
| `?`      | Matches **exactly one character**                     | `$ ls file?.txt` → matches `file1.txt`, `fileA.txt`, etc.      |
| `[abc]`  | Matches **any one character** inside the brackets     | `$ ls file[12].txt` → matches `file1.txt` or `file2.txt`       |
| `[!abc]` | Matches **any one character not inside** the brackets | `$ ls file[!12].txt` → matches `file3.txt`, `fileA.txt`, etc.  |
| `{...}`  | Matches **any of the comma-separated patterns**       | `$ ls {file1,file2}.txt` → matches `file1.txt` and `file2.txt` |
