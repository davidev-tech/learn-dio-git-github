# 🚀 Trabalhando com repositório local

```bash
# Inicializar um repositório Git na pasta atual
git init

# Listar arquivos, inclusive ocultos (.git)
ls -a

# Criar um arquivo vazio
touch README.md

# Ver status dos arquivos
git status

# Adicionar todos os arquivos à staging area
git add .
# ou
git add *

# Remover um arquivo da staging area
git restore --staged nome_do_arquivo

# Criar um commit com mensagem
git commit -m "sua mensagem aqui"
