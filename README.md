Atividade-no-git-Professor-Ronaldo 14/09/2026

1.CRIAR PASTA E INICIALIZAR O GIT cd ~/Downloads mkdir 
atividade-git 
cd atividade-git
git init

2.CONFIGURAR USUÁRIO git config --global user.name Vinicius Maia git config --global user.email viniciusmaia1510@gmail.com

3.CRIAR ARQUIVO HTML touch index.html

4.PRIMEIRO COMMIT git add index.html git commit -m Criar-Index.html

5.CRIAR BRANCH DEVELOP git branch develop git switch develop

6.ALTERAR O INDEX.HTML git add index.html git commit -m Alterar-Index.html

7.CONECTAR AO GITHUB git remote add origin git remote add origin https://github.com/ViniciusMaia1510/Atividade-no-git-Professor-Ronaldo

8.MESCLAR BRANCH DEVELOP COM MAIN git switch master git merge develop
