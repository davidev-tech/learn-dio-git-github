# ⚙️ Configuração inicial do Git

```bash
# Definir nome e email (aparecerão nos commits)
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

# Listar todas as configurações atuais
git config --list

# Remover uma configuração (resetar)
git config --unset user.name
git config --unset user.email