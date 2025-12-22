#computation #linux #shell 

## Definition / Definição

### English
The `join` command in Linux is used to **combine lines of two files** based on a common field (like a database join). The files must be **sorted** on the join field. It is often used to merge related information from different files.

### Português
O comando `join` no Linux é usado para **combinar linhas de dois arquivos** com base em um campo comum (como um "join" em banco de dados). Os arquivos devem estar **ordenados** pelo campo de junção. Ele é frequentemente usado para unir informações relacionadas de arquivos diferentes.

### Basic Syntax / Sintaxe Básica
```bash
join [options] file1 file2
```

### Common Options / Opções Comuns

| Flag | Function (EN)                     | Função (PT)                         | Example                     |
| ---- | --------------------------------- | ----------------------------------- | --------------------------- |
| -1 N | Join on field N of file1          | Une pelo campo N do file1           | `$ join -1 2 file1 file2`   |
| -2 N | Join on field N of file2          | Une pelo campo N do file2           | `$ join -2 3 file1 file2`   |
| -t C | Use C as field delimiter          | Usa C como delimitador de campos    | `$ join -t ',' file1 file2` |
| -a 1 | Include unpaired lines from file1 | Inclui linhas não pareadas do file1 | `$ join -a 1 file1 file2`   |
| -a 2 | Include unpaired lines from file2 | Inclui linhas não pareadas do file2 | `$ join -a 2 file1 file2`   |
