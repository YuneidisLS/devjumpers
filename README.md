
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
