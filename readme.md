Guia básico para eu consultar sempre que precisar usar o git hub
Com o tempo e a prática isso vai ficar automático, mas por enquanto vou usar esse guia.
Estou usando o Terminal do VS CODE mesmo, inclusive estou escrevendo isso nele.
Para abrir o terminal apertamos (Ctrl + ")
Verifique se está na pasta do projeto 
Use os seguintes comandos no Terminal 
Lembre-se que só de apertar o ENTER o comando já inicia então aperte somente quando estiver pronto.

git init (iniciliza o GIT no projeto)

git add README.md (Adiciona o README.MD, eu prefiro já criar ele dentro do VSCODE, tanto faz, mesmo criando manualmente é necessário fazer esse comando)

git commit -m "nome do seu commit" (aqui fazemos o commit, dê o nome que desejar)

git branch -M main (branch principal)

git remote add origin (aqui coloque o link do seu repositório do git)

git push -u origin main (aqui é o PUSH para a branch principal)

Esse é o passo para o PRIMEIRO commit, pois precisamos especificar o repositório e tudo mais.
Depois que isso está predefinido fazemos da seguinte forma

git add (nome do arquivo, EX (README.md) se usarmos (git add .) mandamos tudo que foi alterado) 

git commit -m "nome do seu commit"

git push -u origin main (aqui enviamos o commit para o repositório, e a branch que estamos é a MAIN)
 