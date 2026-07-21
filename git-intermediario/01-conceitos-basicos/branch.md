# Branch

Uma **branch** (ramo) é uma ramificação **dentro do mesmo repositório**.  
Funciona como um "caminho" paralelo que contém os arquivos do projeto, permitindo trabalhar em novas funcionalidades, correções ou experimentos sem mexer na estrutura principal que já está funcionando.

**Principais características:**
- A branch principal costuma ter o nome `main` ou `master`.
- Criar uma branch é como abrir um **laboratório de riscos controlados**: você pode fazer alterações livremente sem comprometer o código estável.
- Cada branch aponta para um commit específico e evolui de forma independente até ser integrada de volta (via merge).

**Comandos essenciais:**
```bash
git branch <nome-da-branch>     # cria uma nova branch
git checkout <nome-da-branch>   # muda para a branch
git checkout -b <nome-da-branch> # cria e já muda para a nova branch
git branch                       # lista as branches locais
