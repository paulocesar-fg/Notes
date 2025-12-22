#computation #linux #shell 

## Definition 

The `grep` commands is one of the most useful tools and Unix systems. It is used to **search for specif words, phrases, or patterns inside text files, and shows the matching lines on your screen**.

### Syntax:

```bash
grep [options] [pattern] [files]
```

### Options

| Option | Function                                                                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------ |
| -i     | Case insensitive search(ex: matches: UNIX; Unix; unix; uNix... are the same word)                            |
| -c     | Displaying the count matches using grep                                                                      |
| -l     | Display the matching filenames using grep                                                                    |
| -w     | This option to grep makes it match only the whole words. By default, grep matches the given string/patterns. |
| -o     | Display matched pattern using grep.                                                                          |
| -n     | Show line number                                                                                             |
| -v     | Inverting the pattern match using                                                                            |
| -e     | Specifies expression, you can  use multiple times(ex: ```grep -e pattern1 -e pattern2 -e pattern3 [file]```) |
| -f     | To read patterns from a file                                                                                 |
