---

<div align="center">
  <h1>📚 Versionamento de Código – Git & GitHub</h1>
  <p>
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    <img src="https://img.shields.io/badge/DIO-FF6F00?style=for-the-badge&logo=digitalocean&logoColor=white" alt="DIO" />
    <img src="https://img.shields.io/badge/B%C3%A1sico-Conclu%C3%ADdo-brightgreen?style=for-the-badge" alt="Básico" />
    <img src="https://img.shields.io/badge/Intermedi%C3%A1rio-Conclu%C3%ADdo-brightgreen?style=for-the-badge" alt="Intermediário" />
  </p>
  <p><em>Anotações e exercícios dos cursos de Git e GitHub da Digital Innovation One, organizados por nível de aprendizado.</em></p>
</div>

---

## 🚀 Estrutura do Repositório

| Curso | Conteúdo Principal | Status |
| :--- | :--- | :---: |
| **Introdução ao Git e GitHub** | Fundamentos, configuração, repositórios local/remoto, SSH | ✅ Concluído |
| **Versionamento Intermediário** | Branches, stash, histórico, manipulação de commits, merge, fork, boas práticas, SemVer | ✅ Concluído |
| **Versionamento Avançado** | Forks (contribuição), permissões, organizações e times, pull request, issues, aliases | ⏳ Planejado |

> 💡 **Nota:** Ambos os cursos estão documentados em arquivos Markdown organizados por tópico. O nível básico está na pasta `git-basico/` e o intermediário na pasta `git-intermediario/`.

---

## 📂 Navegação

### 🌱 Curso Básico – Arquivos Disponíveis
- [🖥️ Comandos do Terminal (Windows)](./git-basico/terminal-windows.md)  
- [🧱 Conceitos Fundamentais do Git](./git-basico/conceitos-git.md)  
- [⚙️ Configuração Inicial](./git-basico/configuracao-inicial.md)  
- [🚀 Repositório Local](./git-basico/repositorio-local.md)  
- [🔐 SSH e Acesso ao GitHub](./git-basico/ssh-e-github.md)  
- [🌐 Repositório Remoto](./git-basico/repositorio-remoto.md)  
- [🧠 Dicas Extras](./git-basico/dicas-extras.md)  

### 🌿 Curso Intermediário – Arquivos Disponíveis

#### 🔹 Conceitos Básicos
- [Branch](./git-intermediario/01-conceitos-basicos/branch.md) – O que é uma branch, ramificações no mesmo repositório  
- [Fork](./git-intermediario/01-conceitos-basicos/fork.md) – Cópia completa do repositório para outro remoto  
- [Merge](./git-intermediario/01-conceitos-basicos/merge.md) – Fusão de branches, fast-forward e merge commit  
- [HEAD](./git-intermediario/01-conceitos-basicos/head.md) – Ponteiro HEAD e relação commit/branch  
- [Repositório Inicial](./git-intermediario/01-conceitos-basicos/repositorio-inicial.md) – Repositório vazio vs. repositório com commit inicial  

#### 🔹 Boas Práticas
- [Por que se importar?](./git-intermediario/02-boas-praticas/importancia.md) – Legibilidade, equipe e versionamento  
- [Commits Atômicos](./git-intermediario/02-boas-praticas/commits-atomicos.md) – Definição, benefícios e dicas práticas  
- [Estrutura da Mensagem](./git-intermediario/02-boas-praticas/estrutura-mensagem.md) – Assunto, corpo, rodapé e exemplos em português/inglês  

#### 🔹 Versionamento
- [SemVer](./git-intermediario/03-versionamento/semver.md) – Formato MAJOR.MINOR.PATCH e significado de cada nível  
- [Conventional Commits](./git-intermediario/03-versionamento/conventional-commits.md) – Especificação e tipos `feat`, `fix`, breaking changes  

#### 🔹 Comandos Práticos
- [Remoto](./git-intermediario/04-comandos-git/remoto.md) – `git remote -v`, `pull`, `push`  
- [Branch (comandos)](./git-intermediario/04-comandos-git/branch.md) – Criação, navegação, renomeação e exclusão  
- [Stash](./git-intermediario/04-comandos-git/stash.md) – Armazenamento temporário de alterações  
- [Histórico](./git-intermediario/04-comandos-git/historico.md) – `git log`, `oneline`, `graph`, `gitk`  
- [Manipulação de Commits](./git-intermediario/04-comandos-git/manipulacao-commits.md) – `reset` (soft/mixed/hard) e `revert`  

### 🚀 Curso Avançado (Planejado)
- **Forks:** contribuição com repositórios de terceiros, sincronização com upstream  
- **Permissões, organizações e times:** gerenciamento de acesso e equipes no GitHub  
- **Pull Request:** criação, revisão, discussão e merge  
- **Issues:** templates, labels, milestones, fechamento automático  
- **Aliases:** criação de atalhos personalizados para comandos Git  

---

## 🛠️ Ferramentas Utilizadas
- **Versionamento:** Git (Git Bash no Windows)  
- **Plataforma:** GitHub  
- **Editor:** VS Code  
- **Curso:** Digital Innovation One (DIO)  

---

## 📝 Como Utilizar Este Repositório

1. Clone o repositório:
   ```bash
   git clone https://github.com/davidev-tech/learn-dio-git-github.git
   ```
2. Acesse os arquivos `.md` dentro das pastas `git-basico/` e `git-intermediario/` para revisar anotações e comandos.

---

## 🎯 Habilidades Desenvolvidas
- Controle de versão local e distribuído  
- Criação e mesclagem de branches  
- Recuperação de estados e manipulação segura do histórico  
- Colaboração via GitHub (fork, pull request)  
- Padronização de commits com SemVer e Conventional Commits  
- Documentação técnica com Markdown  

---

<div align="center">
  <em>“Dominar Git é o primeiro passo para colaborar com o mundo.”</em>
</div>

---
```
