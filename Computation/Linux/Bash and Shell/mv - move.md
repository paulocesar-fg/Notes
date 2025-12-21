#computation #linux #shell 

The `mv` command serves two primary purpose renaming files and directories and moving them a different location.

##### Renaming files and directories:

Sintax :
```bash
mv oldFileName newFileName
```
For directories:
```bash
mv oldDirectoryName newDirectoryName
```
#### Moving files and directories

To move a single file into a different directory

```bash
mv file dir/
```

Moving Multiples files at once:
```bash
mv file1 ... fileN dir/
```
#### Useful Options

| Option | Description                                                                                                                      |     |
| ------ | -------------------------------------------------------------------------------------------------------------------------------- | --- |
| `-i`   | **Interactive:** Prompts for confirmation before overwriting an existing file.                                                   |     |
| `-f`   | **Force:** Overwrites an existing destination file without prompting for confirmation (overrides `-i`).                          |     |
| `-v`   | **Verbose:** Displays a message for each file successfully moved, which is helpful for tracking progress.                        |     |
| `-n`   | **No clobber:** Prevents overwriting an existing file altogether.                                                                |     |
| `-u`   | **Update:** Moves the file only if the source file is newer than the destination file or if the destination file does not exist. | pi  |
