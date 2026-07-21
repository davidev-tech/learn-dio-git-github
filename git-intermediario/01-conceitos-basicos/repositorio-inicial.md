# Repositório vazio × repositório com commit inicial

Quando criamos um repositório remoto **sem** README ou `.gitignore`, ele fica completamente vazio: não possui branch nem commit.

Assim que adicionamos qualquer arquivo (ou o próprio GitHub cria um README), o repositório automaticamente ganha um **commit inicial** e uma branch (geralmente `main`).

Isso é útil para entender por que alguns repositórios novos precisam de `git push -u origin main` enquanto outros já vêm com a branch criada.
