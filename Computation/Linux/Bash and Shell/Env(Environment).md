#computation #linux #shell 

The Linux system uses environment variables to store information that the shell and then process can access.  These variables contain useful data about your user session and system configuration.

You can view the value of a specific variable by prefixing its name with a `$`symbol. For example:

```bash
echo $HOME
```

### What does env Do in Linux

You can use the `env` command to see all the environment variables currently set for your session.

### The importance of the PATH variable

When you type a command, your system searches through these directories to find the corresponding executable file.

The path variable( $PATH ) in Linux is a crucial environment variable that tells the shell which directories to search for executable programs when you type a command.

### Setting an Environment variable for the current session

Use the `export` command to setting an Enviroment Variable

```bash 
export TEST=test
```
After this, if you run:

```bash
echo $TEST
```
The output will be:
```bash
test
```

### Making the environment variable persistent across sessions

Open `~/.bashrc`in the text editor.
Example:
```bash
nano ~/.bashrc
```
Add the export line to the end of the file:
```bash
export TEST=test
```
Save and exit
To apply the changes immediately without reopening the terminal, run:
```bash
source ~/.bashrc
```




