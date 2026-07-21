
# HEAD

O **HEAD** é um ponteiro especial que indica o ponto atual do repositório, normalmente apontando para o **último commit da branch** em que você está trabalhando.

- Visualmente, os commits se comportam como uma pilha: o HEAD está no topo.
- Quando você troca de branch, o HEAD passa a apontar para o último commit dessa outra branch.
- Também é possível um estado "detached HEAD", quando você faz checkout de um commit específico sem estar em uma branch.

> **Regra de ouro:** Não existe branch sem commit, e nem commit sem branch (o Git sempre mantém um ponteiro para a linhagem de commits).
