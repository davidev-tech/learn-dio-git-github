git remote -v serve para listar todos os repositórios remotos configurados no seu projeto, mostrando os seus nomes e as suas respectivas URLs de leitura (fetch) e escrita (push)**

Git Branchs:

git pull origin [nome_branch]
git push origin [nome_branch]
git branch: Lista as branchs locais
git checkout -b [nome_branch] : Ele cria branch e te move para a branch escolhida.
git checkout [nome_branch] : Permite movimentação entre branchs.
git branch [nome_branch] : Cria uma Branch.
git branch -m [novo_nome_branch] : Renomeia a Branch que você ja está.
git branch -m [nome_branch] [novo_nome_branch] : Renomeia a Branch que você escolheu.
git branch -d [nome_branch] : Deleta a Branch escolhida.


Git stash:

git stash save "Mensagem" : Coloca as alterações em index da branch, evitando sujeira entre branchs.
git  stash list: lista a lista de stash das branches.
git stash pop indice: Remove as mudanças do stash.
git stash clear: Apaga a lista dos stashs.


Git Historico:

git log : Mostra todo o historico de commits. -> Para sair da tela de visualização de commit aperte q + enter.
git log [nome_diretorio] : Mostra todo o historico de commits daquele diretorio.
git log --oneline : Trâz o historico de commits de forma resumida.
git log --graph : Trâz o historico de forma mais visual e grafica.
gitk : Trâz o histórico de forma grafica ainda mais visual.

Manipulando commits:

git reset [hash] : Reverte o commit especificado.
git reset [HEAD~quantidade_casas_para_trâs] : Reverte a quantidade de commits especificados em relação a head.
git reset --soft [HEAD~quantidade_casas_para_trâs] : Reverte o commit para o seu estado anterior ao commit, staged.
 git reset --mixed [HEAD~quantidade_casas_para_trâs] : Reverte o commit a um estado anterior ao staged
 git reset --hard [HEAD~quantidade_casas_para_trâs] : Deleta todo aquele commit.
git revert [HEAD~quantidade_casas_para_trâs] : Faz um commit fazendo todo o processo inverso ao commit selecionado.

Obs: Tomar cuidado ao usar o hard, Force ou f. Sempre usar com muita conciencia. Pois pode trazer consequencias irreversiveis.
