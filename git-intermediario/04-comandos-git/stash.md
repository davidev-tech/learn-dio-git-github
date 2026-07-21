
---

```markdown
# Git Stash

O `stash` guarda temporariamente alterações que você não quer commitar ainda, "limpando" o diretório de trabalho. Muito útil para trocar de branch sem carregar modificações indesejadas.

```bash
git stash save "Mensagem"           # guarda as alterações com uma descrição
git stash list                      # lista todas as stashs salvas
git stash pop <indice>              # aplica a stash e a remove da lista
git stash apply <indice>            # aplica a stash mas mantém na lista
git stash drop <indice>             # remove uma stash específica
git stash clear                     # apaga toda a lista de stashs

Nota: `git stash save` foi substituído por `git stash push -m "mensagem"`, mas o `save` ainda funciona.
