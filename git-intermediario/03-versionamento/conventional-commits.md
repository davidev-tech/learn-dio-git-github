# Conventional Commits

É uma convenção para padronizar as mensagens de commit, totalmente alinhada com o SemVer.  
Facilita a leitura do histórico e permite a criação de ferramentas automatizadas (geração de changelogs, versionamento automático, etc.).

## Estrutura básica

<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé opcional]


## Tipos principais (e sua relação com o SemVer)

| Tipo       | Quando usar                                                 | Impacto no SemVer |
|------------|-------------------------------------------------------------|-------------------|
| `feat`     | Nova funcionalidade (feature)                               | **MINOR**         |
| `fix`      | Correção de bug                                             | **PATCH**         |
| `BREAKING CHANGE` (no corpo/rodapé) ou `!` após o tipo | Mudança que quebra compatibilidade | **MAJOR** |

Exemplos:
- `feat: adiciona tela de login` → **MINOR**
- `fix: corrige erro ao salvar formulário` → **PATCH**
- `feat!: remove suporte ao legado` (ou `feat` com `BREAKING CHANGE` no corpo) → **MAJOR**

Outros tipos comuns (não definidos na especificação, mas amplamente adotados): `docs`, `style`, `refactor`, `test`, `chore`, `perf`, `ci`, `build`.

🔗 Referência oficial: [conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)
