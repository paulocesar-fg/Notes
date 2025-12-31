#computation #vcs #git 

---
## Cues

- How to ignore files with specific name patterns?
- What is the `.gitignore` file?

---

## Notes

If you want to ignore specific files, you can create a **`.gitignore`** file and list all file names or patterns that Git should ignore.

The **`.gitignore`** file tells Git which files or directories should not be tracked or committed to the repository.

### Example: Ignore a specific file

To ignore the file `ignoredFile.txt`, add the following line to your `.gitignore` file:

```gitignore
ignoredFile.txt
```

Example: Ignore all .txt files

To ignore all files with the .txt extension:

*.txt

Example: Ignore a specific directory

To ignore an entire directory:

dir/

In other words, add to the .gitignore file all files and patterns that you want Git to ignore.


----
## Summary( Portuguese)

Adicione no arquivo .gitignore todos os arquivos, diretórios ou patterns que você deseja que o git ignore.