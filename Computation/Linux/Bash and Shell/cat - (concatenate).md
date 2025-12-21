#computation #linux #shell 

`cat` command in Linux (short for "**concatenate**") is a versatile utility used primarily to ==read, display, and manipulate text files from the command line==. 

Core Functions

- **Display file contents:** The most common use is to output the entire content of one or more files to the standard output (your terminal screen).
    - _Example:_ `cat filename.txt`
- **Concatenate files:** It can combine the content of multiple files into a single, continuous output, which can then be redirected to a new file.
    - _Example:_ `cat file1.txt file2.txt > combinedfile.txt`
- **Create new files:** Using output redirection (`>`), you can create a new file and type content directly into the terminal until you press **Ctrl+D** to save and exit.
    - _Example:_ `cat > newfile.txt`
- **Append to files:** Using the append redirection operator (`>>`), you can add new content to the end of an existing file without overwriting its original contents.
    - _Example:_ `cat >> existingfile.txt` 

Common Options

The `cat` command offers several options to modify its behavior: 

- `-n`: Numbers all output lines.
- `-b`: Numbers only non-blank lines (suppresses numbers on empty lines).
- `-s`: Squeezes multiple adjacent blank lines into a single blank line.
- `-E`: Displays a `$` character at the end of each line to mark line endings.
- `-T`: Displays tab characters as `^I` for better visibility.
- `-A`: An all-encompassing option equivalent to `-vET`, showing all non-printing characters, tabs, and line endings. 

Advanced Uses

The `cat` command is often combined with pipes (`|`) to send its output as input to other commands for further processing, such as sorting or filtering. 

- _Example:_ To display the contents of a large file page by page, you can pipe the output to the `less` command: `cat largefile.txt | less`