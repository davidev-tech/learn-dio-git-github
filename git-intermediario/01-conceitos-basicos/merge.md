# Merge

O **merge** é a fusão de duas branches, normalmente para unir o trabalho de uma branch de funcionalidade (ou correção) de volta à branch principal (ex.: `main`).

**Funcionamento básico:**
- Após concluir as alterações na branch secundária, você faz um merge para incorporar essas mudanças na branch de destino.
- O Git tenta combinar os históricos automaticamente. Se houver conflitos (alterações incompatíveis no mesmo trecho de arquivo), será necessário resolvê-los manualmente.

**Tipos de merge comuns:**
- **Fast-forward**: quando a branch de destino não recebeu novos commits, o ponteiro simplesmente avança.
- **Merge commit**: quando ambas as branches têm commits novos, o Git cria um commit extra que une as duas pontas.

**Comandos essenciais:**
```bash
git checkout main                # vá para a branch que receberá as mudanças
git merge <nome-da-branch>       # faz o merge da branch especificada na branch atual
