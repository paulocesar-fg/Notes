#computation #vcs #git 

---
## Cues

* What does "snapshots, not differences" mean ? 
* How does Git differ from delta-based VCS ?
* Why are most Git operation fast ?
* How does Git ensure data integrity ?
* Why is it hard to lose committed data in Git ?

---
## Notes

### Snapshots, not differences

Git stores data as a series of **snapshots** of the entire project, rather than as file-based differences(deltas)

Each commit represents the complete state of the repository at given moment.

Unchanged files **are not duplicated**; Git stores references(links) to previous stored objects.

### Nearly Every Operation is Local

Because each developer has a full copy of the repository history, most Git operation are performed locally. **This makes git fast and allows users to work offline**.

### Git Has Integrity

All data in Git is checksummed using SHA-1 hashes.

Any change to files or history is detectable, ensuring data integrity.

### Git Generally Only Adds Data

Git operations mostly add new data instead of deleting existing data.

Once committed it is difficult to lose data, which makes experimentation safer.

---
## Summary(Portuguese)

O Git é um VCS que armazena a "história"
 como um snapshot(uma espécie de "foto") representando um estado completo em dado momento; os arquivos não alterados são apenas referenciados(não duplicados).

Quase todas as operações são locais.

Git tem integridade - é impossível mudar o conteúdo de algum arquivo ou diretório sem que o git saiba; para isso ele usa SHA-1.

Git minimiza a perda de arquivos, tornando a experimentação segura.
