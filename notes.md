COMANDOS DO GIT

PARA ADICIONAR A LISTA DE COMMITS
git add.

PARA FECHAR UM COMMIT
git commit -m "mensagem"

PARA VER OS COMMITS  
git log ou git show-branch --

PARA ENVIAR O COMMIT PARA A BRANCH MAIN
git push origin main (ou o nome da sua branch)

PARA FAZER UM DOWNLOAD DA BRANCH PRINCIPAL E TRAZER AS ALterações PARA SUA BRANCH  
git pull
git pull origin main 

QUANDO QUISER MESCLAR ALGUMA ALTERAÇÃO DA SUA BRANCH COM A MAIN, USAR:
git merge --abort (para sair do estado de mesclagem)
e depois
git mergetool (para resolver conflitos)

SE HOUVER CONFLITO NO ARQUIVO, VAI ABRIR EM UM EDITOR DE TEXTO COM OS CONFLICTOS, RESOLVA E SALVE O ARQUIVO.

PARA VOLTAR PRA UMA VERSÃO ANTERIOR 
git checkout [commit]

PARA VER O QUE FOI MODIFICADO EM UMA VERSÃO ESPECÍFICA 
git diff [commit1]..[commit2] (para ver as diferenças entre dois commits)
ou
git show [commit] (para ver o que foi feito em um determinado commit)

PARA BUSCAR ALGUMA COISA NO HISTÓRICO  DE COMMITS 
git grep "palavra" (procura por uma palavra no histórico de commits)

PARA FAZER UMA BRANCH COM COPY DA MASTER
git branch nomeDaBranch