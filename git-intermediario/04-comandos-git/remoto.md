# Comandos remotos

## Visualizar repositórios remotos

```bash
git remote -v

Lista todos os repositórios remotos configurados no projeto, mostrando seus nomes e as respectivas URLs de leitura (`fetch`) e escrita (`push`).

git pull origin <nome_branch>    # traz as alterações do remoto e mescla com a branch local
git push origin <nome_branch>    # envia os commits locais para o repositório remoto

`origin` é o nome padrão do repositório remoto, mas pode haver outros.
