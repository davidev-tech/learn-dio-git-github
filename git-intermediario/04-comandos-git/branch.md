# Gerenciamento de Branches

```bash
git branch                          # lista as branches locais
git branch <nome>                   # cria uma nova branch
git checkout <nome>                 # muda para a branch
git checkout -b <nome>              # cria e já muda para a branch

git branch -m <novo_nome>           # renomeia a branch atual
git branch -m <velho> <novo>        # renomeia uma branch específica

git branch -d <nome>                # deleta a branch (seguro, só apaga se o merge já foi feito)
git branch -D <nome>                # força a exclusão (cuidado!)

## Merge entre branches

git checkout <branch_destino>
git merge <branch_origem>           # mescla a branch origem na destino**
