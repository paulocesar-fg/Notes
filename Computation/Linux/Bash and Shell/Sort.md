The `sort` command is useful for sorting lines.

```plaintext
file1.txt 
dog 
cow 
cat 
elephant 
bird 

$ sort file1.txt 
bird 
cat 
cow 
dog 
elephant
```
You can also do a reverse sort:

```plaintext
$ sort -r file1.txt 

elephant
dog
cow
cat
bird
```
And also sort by numerical value:

```plaintext
$ sort -n file1.txt 
bird 
cat
cow
elephant
dog 
```