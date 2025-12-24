#computation #vcs 

## Cues

* What is Version Control System ?
* What is Local VCS ?
* What is Centered VCS(i.e, CVCS) ?
* What is Distributed VCS(i.e, DVCS) ?
---

## Notes

### Definition

Version Control Systems(VCSs) is a systems that records changes to a file or set of files over time so that you can recall specific version later.


### Local Version Control System(LVCS)

![[local version control systems.png]]


Local Version Control is the simplest form of version control. It works **only on a single machine**, without networking or collaboration. 

**Key characteristics:**

- Tracks file changes **locally**
- No central or remote repository
- No built-in collaboration
- High risk of data loss
- Limited history and automation

### Centered Version System Control (CVSC)

![[Centered VCS.png]]

A CVCS uses a single central server to store all versions of files. Users must connect to the server to commit, update, or view history. Examples: CVS and Subversion(SVN).

In CVCS, administrators have more control. However, users only have the **latest state** of the repository, not the full history. Therefore, if the central server fails, **all data can be lost**.

### Distributed Version Control System(DVCS)

![[Distributed Version Control System.png]]

In a DVCS, each developer has a **full copy(clone) of the repository**, including the entire history, on their local machine. Furthermore, there can be a **central remote repository** that gathers and shares commits. Ex: Git and mercurial.

--- 
## Summary(Português)

1) Um VCS é um sistema que permite o controle de versionamento de arquivos no decorrer do tempo. 

2) Um VCS local é um VCS onde os arquivos e suas versões ficam inteiramente armazenados em uma máquina local.

3) Um CVCS é um CVS onde há um repositório remoto central e os desenvolvedores alteram-o.
4) 
5)  Um DVCS  é um sistema de versionamento distribuído, onde cada desenvolvedor possui um cópia(clone) completa de toda a história do repositório em suas máquinas locais, além dissos pode-se compartilhar os commits em repositórios remotos.