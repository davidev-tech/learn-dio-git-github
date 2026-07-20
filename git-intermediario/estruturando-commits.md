Porque me importar?

melhor legibilidade do histórico
Amigável para novos desenvolvedores
Amigável ao versionamento semântico


Commits atômicos:

Não devemos misturar implementações diferentes em um mesmo commit ex.: Mudar a logica de negocio do projeto e a estilização do projeto em um unico commit. Se der um problema em uma das alterações, ao reverter o commit acabaremos revertendo uma implementação já funcional. Cada commit deve mudar uma única coisa no projeto e serem independentes entre si.

dicas:

1. **Planeje antes de codar:**  
    Identifique as pequenas etapas lógicas da tarefa.
    
2. **Use `git add -p` (modo patch):**  
    Permite selecionar trechos específicos de alterações para montar commits focados, mesmo que você tenha mexido em várias coisas ao mesmo tempo.
    
3. **Faça commits frequentes:**  
    Não espere acumular 20 mudanças. A cada passo concluído, faça o commit.
    
4. **Mantenha o build verde:**  
    Um commit atômico não deve quebrar a compilação nem os testes. Rode os testes localmente antes de commitar.
    
5. **Escreva boas mensagens:**  
    A primeira linha deve resumir o _que_ e o _porquê_ da mudança. Se precisar de mais detalhes, use o corpo do commit.

Português x Inglês

A linguagem dependerá exclusivamente do contexto da empresa e projeto.


Estrutura commit

Assunto
Corpo
Rodapé


Assunto

Curto e compreensível até 50 caracteres
Começar com letras maiúscula
Não terminar em ponto .
Escrito de forma imperativa


Em inglês use o imperative mood

Add a feature                        Added a feature
modify an existing feature    Modified an existing feature
Remove a feature                  Removed a feature


If applied , this commit will ...

if applied, this commit will add payment integration
if applied, this commit will update database configurations
if applied, this commit will remove redundant code


Em Português use a voz imperativa

Adiciona a funcionalida x            Funcionalidade x adicionada

Modifica uma funcionalidade existente            Funcionalidade y modificada

Remove a funcionalidade y            Funcionalidade y removida

Se aceito, esse commit ...

Se aceito, esse commit adiciona método de pagamento

Se aceito, esse commit atualiza configurações do banco de dados

Se aceito, esse commit remove código redundante


Corpo

Adicione detalhes ao commit
Tente quebrar a linha em 75 caracteres
Identifique sua audiência
Explique tudo
Use markdown


Rodapé

Referencie assuntos relacionado

issues:

histórico de issues que vai de 1 a infinito.


Abra um editor como o vim:

titulo: Adiciona mensagem de boas vindas                                                                                          
corpo: Esse commit modifica o README.md adicionando uma mensagem de boas vindas        amigável para novos visitantes. Esse commit faz uso de:     

-Markdown                    
-Sarcasmo


Rodape: Closes #1  


Commits Semânticos
Conventional Commits

Semantic Versioning

        3 . 2 . 3
    MAJOR/MINOR/PATCH

MAJOR: Maior numero da versão / Sempre que introduzirmos uma funcionalidade que quebre a compatibilidade. Alteração muito grande.

MIJOR: Menor versão / Implementa uma funcionalidade sem que haja a quebra de compatibilidade. Uma alteração menor.

PATCH: Pequenas alterações do dia a dia como correções de bugs.

https://semver.org/


Conventional Commits

A especificação do Conventional Commits é uma convenção simples para utilizar nas mensagens de commit. Ela define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas baseadas na especificação. Esta convenção se encaixa com o SemVer, descrevendo os recursos, correções e modificações que quebram a compatibilidade nas mensagens de commit.

site: https://www.conventionalcommits.org/en/v1.0.0/