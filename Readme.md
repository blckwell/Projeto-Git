// CONFIGURANDO TOKEN GITHUB/ADICIONANDO ARQUIVO DO DISPOSITIVO LOCAL PARA REPOSITÓRIO GITHUB.

$ git init
Initialized empty Git repository in C:/Users/tecwe/OneDrive/Área de Trabalho/Projeto Git/.git/

$ git add .

$ git config --global user.name "Wellington Gomes";

$  git config --global user.email "wgmachado@inf.ufpel.edu.br"

$ git branch -m main

$ git remote add origin https://github.com/blckwell/Projeto-Git.git

$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   Readme.md


$ git commit -m "meu primeiro commit"
[main (root-commit) de5ed3f] meu primeiro commit
 1 file changed, 1 insertion(+)
 create mode 100644 Readme.md

$ git status
On branch main
nothing to commit, working tree clean

$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 233 bytes | 233.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/blckwell/Projeto-Git.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

$ git login
git: 'login' is not a git command. See 'git --help'.

The most similar command is
        column

$ git log
commit de5ed3f81de9a421daeecce31207684d50a039d6 (HEAD -> main, origin/main)
Author: Wellington Gomes <wgmachado@inf.ufpel.edu.br>
Date:   Sat Dec 31 12:10:33 2022 -0300

    meu primeiro commit
