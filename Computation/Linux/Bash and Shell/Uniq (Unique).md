#computation #linux #shell 

The Linux `uniq` command is use to remove all repeated lines in a file.

#### Syntax:
```bash
$ uniq [Option]  [input_file] [output_file]
```
* input_file: The file containing lines to process.
* output_file(optional): The file to save the result.

### Key Options

| Option | Function                                                                   |
| ------ | -------------------------------------------------------------------------- |
| -c     | Precedes each output line with the number of occurrences in the input file |
| -d     | Display only the lines that are repeated(i.e, duplicates)                  |
| -u     | Display only the lines that are unique(i.e, that appears only once)        |

#### Importance of sorting

The Importance of Sorting

A critical detail about the uniq linux command is that it only detects duplicate lines if they are directly adjacent to each other. If the duplicates are scattered throughout the file, uniq will not identify them.

Consider this version of reading.txt where duplicates are not adjacent:

book
paper
book
paper
article
magazine
article

Running uniq on this file will produce a surprising result:

$ uniq reading.txt
book
paper
book
paper
article
magazine
article

No lines were removed because no two identical lines were next to each other. To solve this, you must first sort the file's contents. By piping the output of sort into uniq, you ensure that all identical lines become adjacent, allowing uniq to work correctly. This combination is a powerful and common pattern in shell scripting.

$ sort reading.txt | uniq
article
book
magazine
paper