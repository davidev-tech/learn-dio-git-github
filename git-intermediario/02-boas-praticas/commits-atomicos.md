# Commits Atômicos

## Definição
Cada commit deve conter **uma única mudança lógica** no projeto, sem misturar implementações diferentes.

**Exemplo do que NÃO fazer:**  
Alterar a lógica de negócio e a estilização do projeto no mesmo commit.  
Se houver um problema na estilização e você precisar reverter, a lógica de negócio (que estava correta) será desfeita junto.

**Benefícios:**
- Reversões seguras e cirúrgicas
- Histórico fácil de entender
- Revisão de código mais eficiente

## Dicas práticas

1. **Planeje antes de codar**  
   Identifique as pequenas etapas lógicas da tarefa.

2. **Use `git add -p` (modo patch)**  
   Permite selecionar trechos específicos de alterações, mesmo que você tenha mexido em várias coisas ao mesmo tempo.

3. **Faça commits frequentes**  
   Não acumule 20 mudanças. A cada passo concluído, faça o commit.

4. **Mantenha o build verde**  
   Um commit atômico não deve quebrar a compilação nem os testes. Rode os testes localmente antes de commitar.

5. **Escreva boas mensagens**  
   A primeira linha deve resumir *o quê* e *por quê* da mudança. Se precisar de mais detalhes, use o corpo do commit.
