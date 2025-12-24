#computation #vcs #git 

---
## Cues

* What are tracked files and untracked files ? 
* How you can check the status of your files ?

---

### Working directory two states

Each file in working directory can be in one of two states: tracked and untracked.

### Untracked Files

Are any files in working directory that were not in your last snapshot and are not in your staging area. In short, are the files that the Git unknows.

### Tracked Files 

Are files that were in the last snapshot. They can be unmodified , modified, or staged. In short, are the files that the Git knows.


### Checking the Status of your files

For this, use ```git status``` command. For more information use the ```git help status```. 

![[git - records flow.png]]
