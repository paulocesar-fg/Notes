
#computation #linux #shell 

The  `alias` command lets you define a custom name for any command or sequence of commands.

#### Creating temporally Alias

Syntax:
```bash
alias newCommandName = 'commands'
```
Example:
```bash
alias ll = 'ls -la'
```
To use:
```bash
ll
```

#### Making an Alias Permanent

To make  a *command alias in Linux* permanent, you need to add it to your shell's configuration file. For the bash shell, this file is typically  `~/.bashrc`.

#### Removing Alias
```bash
unalias alias_name
```
#### Removing Permanent alias

To remove permanent alias, you must also delete  its definition from your bash configuration file( `~/.bashrc`).


