# Artigos
Repositorio para os conteúdos produzidos para meus artigos


You simply need to be in your root folder and then add the submodule folder.

#git submodule add <url>

Now when you clone the project you simply need to init and update the submodule

#git submodule init
#git submodule update

Git 1.8.2 features a new option --remote

#git submodule update --remote --merge

will fetch the latest changes from upstream in each submodule, merge them in, and check out the latest revision of the submodule. As [the docs][1] put it:

