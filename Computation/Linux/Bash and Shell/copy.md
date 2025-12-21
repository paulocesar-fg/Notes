#computation #linux #shell 

In the simplest form, `cp` command copy files.

```bash
cp file1 file2
```

To copy a number of files to a directory(folder) named *dir*, try this instead:

```bash
cp file1 ... fileN dir/
```

#### Copying Directories Recursively

If you try to copy a directory, using *cp* without any options, you will receive an error for this, you must use the -r(Recursive flag)

```bash
cp -r dir destinationDir 
```

#### Useful Options

The `cp` command offers many options to customize its behavior.

|Option|
|---|

||Description|
|---|---|
|**`-i`** (interactive)|Prompts the user for confirmation before overwriting an existing file.|
|**`-n`** (no clobber)|Prevents existing files from being overwritten.|
|**`-v`** (verbose)|Explains what is being done by printing a message for each copied file.|
|**`-p`** (preserve)|Preserves file attributes (mode, ownership, timestamps, etc.) of the original file in the copy.|
|**`-a`** (archive)|An enhanced version of `-p` and `-r`, it copies files and directories recursively while preserving all file attributes and symbolic links.|
|**`-u`** (update)|Copies the file only if the source file is newer than the destination file or if the destination file does not exist.|

For transferring files securely between different machines over a network, the `scp` command is used, which encrypts the data transfer via SSH
