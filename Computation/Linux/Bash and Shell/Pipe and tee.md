#computation #linux #shell 

### Understanding the pipe operator

The pipe operator `|` is an important operator. It takes the [[Standard Output - Stdout | Standard Output(Stdout)]] of the command on its left and uses it as the [[Standard Input - Stdin | Standard Input(Stdin)]] for the command on its right.

For example:

```bash

ls -la /etc | less
```

### Splitting output with the Tee command

What if you want to see the output on screen and save it to file simultaneous ? This is where `tee`command comes in. The pipe and tee command in Linux is a classic combination for logging and monitoring.

```bash 
ls | tee peanuts.txt
```
After running this, you will see the output of `ls` on your terminal. If you also check the content of  `peanuts.txt`, you will find the exact same information.

#### Combining Pipe and Tee

For example, you can use the Linux pipe tee combination to view and save output before further filtering.

```bash
ls -la /etc | tee etc_listing.txt | grep "conf"
```

