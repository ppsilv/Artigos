# Artigos
Repositorio para os conteúdos produzidos para meus artigos

```diff

No diretorio raiz do repo PRINCIPAL crie o modulo com os comandos abaixo
! - git submodule add <url do repo>
! - git commit -m "Added <nome do repo> submodule"

Esses comandos devem ser usados no diretorio raiz do repo PRINCIPAL quando
se faz um clone do repo PRINCIPAL
+ - git submodule init
! - git submodule update 

Esses comandos devem ser usados no diretorio raiz do repo PRINCIPAL quando
algum ou todos os repos dos modulos forem alterados.
git add <nome do repo alterado>
git commit -m "Upgraded <nome do repo alterado> to version XYZ"


This command must be used in repo Artigos/ when nested repo has changes
! - git submodule update --remote --merge

will fetch the latest changes from upstream in each submodule, merge them in, and check out
the latest revision of the submodule. As [the docs][1] put it:

NUNCA ALTERAR OS MODULOS NO REPO Artigos sempre alterar nos seus respectivos
repos.
e fazer os merges em Artigos.

