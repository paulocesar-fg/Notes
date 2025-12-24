
#computation #vcs #git 

---
## Cues

* What are the three states in Git ? 
* Difference between modified and staged ?
* What is the staging area(index)?
*  Where is committed data stored ?
* Why is the Git directory is important ?


---
## Notes

### The three states in Git

##### Modified
The file has been changed in the working directory but has not been saved to the git database.

##### Staged 
The modified file has been added to the staging area and is prepared to be included in the next commit.

##### Committed
The file is safely stored as a snapshot in Git's local database.

### The three main areas

##### Working directory 
A checkout of a specific version of the project. Files are extracted from the git directory and placed on disk for editing.

##### Staging Area(index)
A file inside the Git directory that records what will git into next commit.

##### Git directory
Stores all metadata and the object database. This is the core of the repository and is copied when cloning.

### Basic Git workflow

1- Modify files in the working directory;
2 - Stage selected changes into the staging area.
3 - Commit the staged snapshot into the git directory.

---

## Summary(Portuguese)

O Git gerencia os arquivos através de 3 estados principais: modified(modificado), preparado(staged),e commited(comitado). Usando o diretório de trabalho(working directory) a área de preparação(staging area), e o diretório git(.git) para controlar como as mudanças se tornam snapshots.

Resumindo:

Working Directory - você modifica;

Staging Area - você escolhe o que vai salvar(git add)

Repository(committed) - você grava permanetemente(git commit).
