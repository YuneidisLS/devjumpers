
yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop
$ mkdir EjercicioFinal-Git-GitHub

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop
$ cd EjercicioFinal-Git-GitHub

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub
$ git clone https://github.com/YuneidisLS/devjumpers.git
Cloning into 'devjumpers'...
warning: You appear to have cloned an empty repository.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub
$ touch README.md

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub
$ git status
fatal: not a git repository (or any of the parent directories): .git

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub
$ cd devjumpers

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git commit -m"commit inicial"
[main (root-commit) aa554fc] commit inicial
 1 file changed, 20 insertions(+)
 create mode 100644 README.md

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 7 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 424 bytes | 424.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/YuneidisLS/devjumpers.git
 * [new branch]      main -> main

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git ls
git: 'ls' is not a git command. See 'git --help'.

The most similar command is
        lfs

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ touch privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ mkdir privada

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        privado.txt

nothing added to commit but untracked files present (use "git add" to track)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   privado.txt


yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git commit -m "Se crea archivo privado.txt y carpeta privada"
[main dab058e] Se crea archivo privado.txt y carpeta privada
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 7 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 297 bytes | 297.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/YuneidisLS/devjumpers.git
   be8dd8a..dab058e  main -> main

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add privada

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add privada

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git commit -m "se agrega carpeta privada"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ status
bash: status: command not found

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ cd privada


yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ touch .gitignore

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   .gitignore
        modified:   README.md


yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git commit -m"se crea el archico para ignorar la carpeta y archivo privado"
[main bab5ac2] se crea el archico para ignorar la carpeta y archivo privado
 2 files changed, 106 insertions(+)
 create mode 100644 .gitignore

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 7 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.31 KiB | 1.31 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/YuneidisLS/devjumpers.git
   dab058e..bab5ac2  main -> main



yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop
$ cd EjercicioFinal-Git-GitHub

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub
$ cd devjumpers

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ touch 1.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git branch v0.2

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git checkout v0.2
Switched to branch 'v0.2'

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ ^C

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ touch 2.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git status
On branch v0.2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        1.txt
        2.txt

nothing added to commit but untracked files present (use "git add" to track)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git status
On branch v0.2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   1.txt
        new file:   2.txt


yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git commit -m "Se creaa rama, y ficheros 1.txt,2.txt"
[v0.2 82dc09e] Se creaa rama, y ficheros 1.txt,2.txt
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git push -u origin v0.2
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 7 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 327 bytes | 327.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'v0.2' on GitHub by visiting:
remote:      https://github.com/YuneidisLS/devjumpers/pull/new/v0.2
remote:
To https://github.com/YuneidisLS/devjumpers.git
 * [new branch]      v0.2 -> v0.2
branch 'v0.2' set up to track 'origin/v0.2'.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git merge v0.2
Updating cb5dd0d..82dc09e
Fast-forward
 1.txt | 0
 2.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1.txt
 create mode 100644 2.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
1.txt  2.txt  README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/YuneidisLS/devjumpers.git
   cb5dd0d..82dc09e  main -> main
   
$ git status
$ git add .
$ git commit -m"Se pone texto en el archivo1.txt"
$ git checkout v0.2
Aca vamos otra vez al archio 1.txt y agregamos un adios 
$ git add .
$ git commit -m"se agrefo texto en el archico 1.txt"
$ git checkout main
$ git merge v0.2
luego aca nos sale un conflicto vamos al archico 1.txt y lo abrimos con visual 
$ git branch --merge
$ git branch --no-merge
$ git add .
$ git commit -m "conflictos resueltos"
$ git merge
$ git push
