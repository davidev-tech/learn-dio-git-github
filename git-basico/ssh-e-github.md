
---

### 📄 `ssh-e-github.md`
```markdown
# 🔐 Chave SSH e acesso ao GitHub

## Gerar e configurar chave SSH

```bash
# Gerar par de chaves pública/privada
ssh-keygen -t ed25519 -C "seu@email.com"

# Acessar a pasta .ssh
cd /c/Users/seu_usuario/.ssh/

# Exibir chave pública (copie para o GitHub)
cat id_ed25519.pub

# Iniciar o ssh-agent
eval $(ssh-agent -s)

# Passar a chave privada ao agent
ssh-add id_ed25519
## Token vs Chave SSH

- **Token de acesso pessoal**: credencial temporária que substitui a senha.
    
- **Chave SSH**: autenticação criptografada entre duas máquinas.
  
---

### 📄 `repositorio-remoto.md`
```markdown
# 🌐 Vinculando e sincronizando repositório remoto

```bash
# Adicionar um remote chamado origin
git remote add origin <URL>

# Enviar commits para o repositório remoto
git push -u origin main   # (ou master)

# Atualizar o repositório local com mudanças remotas
git pull