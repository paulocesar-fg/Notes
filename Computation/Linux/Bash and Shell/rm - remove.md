#computation #linux #shell 

## Definition

The `rm` command in Linux **removes** (i.e., deletes) files and directories.

### Basic Usage
```bash
rm [file]
```

### Removing Directories

To remove directories, use the `-r` (recursive) flag:

```bash
rm -r [directory]
```

### Common Options

| Flag             | Function                             | Example               |
| ---------------- | ------------------------------------ | -------------------- |
| -i (interactive) | Asks for confirmation before deleting | `$ rm -i [file]`      |
| -f (force)       | Forces the operation without prompts | `$ rm -f [file]`      |
| -v (verbose)     | Displays the files being removed     | `$ rm -v [file]`      |

### Danger Flag

The combination of `-r` and `-f` will delete directories **recursively** and **forcefully**, which can be very dangerous:

```bash
rm -rf [directory]
```

> ⚠️ **Warning:** Use `rm -rf` with extreme caution. It will delete everything in the specified directory without any confirmation and cannot be undone.
