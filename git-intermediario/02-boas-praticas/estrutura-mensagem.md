# Estrutura da Mensagem de Commit

A mensagem pode conter três partes:
- **Assunto** (obrigatório)
- **Corpo** (opcional)
- **Rodapé** (opcional)

## Assunto

- Curto e compreensível (até **50 caracteres**)
- Começar com **letra maiúscula**
- **Não** terminar com ponto final
- Escrito de forma **imperativa** (como uma ordem)

### Exemplos em inglês (imperative mood)

Use a frase mental: *"If applied, this commit will..."*

- `Add payment integration`
- `Update database configurations`
- `Remove redundant code`

### Exemplos em português (voz imperativa)

Use a frase mental: *"Se aceito, esse commit..."*

- `Adiciona método de pagamento`
- `Atualiza configurações do banco de dados`
- `Remove código redundante`

## Corpo

- Adicione detalhes que o assunto não conseguiu explicar
- Tente quebrar as linhas em aproximadamente **75 caracteres**
- Identifique sua audiência (o que o time precisa saber?)
- Explique o **contexto** e a **motivação** da mudança
- Pode usar **Markdown** (listas, links, trechos de código)

## Rodapé

- Referencie issues, tickets ou pull requests relacionadas
- Formatos comuns:  
  `Closes #1`  
  `Fixes #42`  
  `Refs #3`

> **Dica:** Use uma linha em branco entre assunto, corpo e rodapé.

## Exemplo completo (usando editor como Vim)

Adiciona mensagem de boas-vindas

Esse commit modifica o README.md adicionando uma mensagem de boas-vindas  
amigável para novos visitantes. Esse commit faz uso de:

- Markdown
    
- Sarcasmo
    

Closes #1
