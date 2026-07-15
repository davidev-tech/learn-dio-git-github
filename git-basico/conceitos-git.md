# 🧱 Conceitos fundamentais do Git

## Blob
Armazena os dados brutos do arquivo (a “caixa” de metadados).

## Tree
Funciona como um diretório: mapeia os nomes dos arquivos e os organiza hierarquicamente. É uma etiqueta criptografada que identifica os blobs.

## Commit
É um registro no histórico. Armazena o autor, data, alterações e uma referência à árvore (tree) do projeto naquele momento.

## Estados dos arquivos
- **Tracked**: arquivos que o Git já conhece.
  - **Unmodified**: não modificados desde o último commit.
  - **Modified**: alterados, mas não adicionados à staging area.
  - **Staged**: prontos para o próximo commit.
- **Untracked**: arquivos novos, que o Git ainda não monitora.

Git e GitHub são diferentes:

Git: Sistema de versionamento de código.
GitHub: Plataforma de desenvolvimento Colaborativa.