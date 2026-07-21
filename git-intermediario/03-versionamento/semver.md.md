# Versionamento Semântico (SemVer)

Formato padrão: **MAJOR.MINOR.PATCH**  
Exemplo: `3.2.3`

- **MAJOR** (versão principal)  
  Aumenta quando introduzimos uma mudança que **quebra a compatibilidade** com versões anteriores.  
  Ex.: remover um endpoint público, alterar o comportamento de uma função crítica.

- **MINOR** (versão secundária)  
  Aumenta quando adicionamos uma funcionalidade **sem quebrar a compatibilidade**.  
  Ex.: novo endpoint, nova opção em um comando, funcionalidade opcional.

- **PATCH** (correção)  
  Pequenas alterações do dia a dia, como correções de bugs que não alteram a API pública.  
  Ex.: corrigir um cálculo errado, tratar um erro inesperado.

> **Resumo visual:**  
> Quebrou algo? → **MAJOR**  
> Adicionou algo novo sem quebrar? → **MINOR**  
> Corrigiu um bug? → **PATCH**

🔗 Referência oficial: [semver.org](https://semver.org/)