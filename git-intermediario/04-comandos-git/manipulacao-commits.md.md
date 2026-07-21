
---


```markdown
# Manipulando Commits (reset e revert)

## git reset

O `reset` move o ponteiro da branch para um commit anterior, desfazendo alterações.

```bash
git reset <hash>                               # desfaz até o commit especificado (mantém alterações no working directory)
git reset HEAD~<n>                             # volta n commits a partir do HEAD

git reset --soft HEAD~<n>                      # desfaz o commit, mas mantém as mudanças no stage (staged)
git reset --mixed HEAD~<n>                     # (padrão) desfaz o commit e tira do stage, mas mantém os arquivos modificados
git reset --hard HEAD~<n>                      # APAGA completamente o commit e todas as alterações


> ⚠️ **Cuidado com `--hard` e `push --force`:**  
> Esses comandos reescrevem o histórico e podem causar perda irreversível de dados. Use com muita consciência.

## git revert

O `revert` é mais seguro: ele cria um **novo commit** que desfaz as alterações de um commit anterior, preservando o histórico.

git revert <hash>                 # reverte um commit específico
git revert HEAD~<n>               # reverte o n-ésimo commit anterior ao HEAD

**Diferença fundamental:**

- `reset` → reescreve a história (perigoso se compartilhado)
    
- `revert` → adiciona um commit de "anti-mudança" (seguro para branches remotas)