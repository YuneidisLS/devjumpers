
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
yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop
$ cd EjercicioFinal-Git-GitHub

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub
$ cd devjumpers

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   1.txt

no changes added to commit (use "git add" and/or "git commit -a")

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git commit -m"Se pone texto en el archivo1.txt"
[main 628df62] Se pone texto en el archivo1.txt
 1 file changed, 1 insertion(+)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git checkout v0.2
Switched to branch 'v0.2'
Your branch is up to date with 'origin/v0.2'.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git commit -m"se agrefo texto en el archico 1.txt"
[v0.2 d3fb05d] se agrefo texto en el archico 1.txt
 1 file changed, 1 insertion(+)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git cheockout main
git: 'cheockout' is not a git command. See 'git --help'.

The most similar command is
        checkout

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (v0.2)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git merge v2.0
merge: v2.0 - not something we can merge

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git merge c0.2
merge: c0.2 - not something we can merge

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ gi merge v0.2
bash: gi: command not found

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git merge v0.2
Auto-merging 1.txt
CONFLICT (content): Merge conflict in 1.txt
Automatic merge failed; fix conflicts and then commit the result.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main|MERGING)
$ git brach --merge
git: 'brach' is not a git command. See 'git --help'.

The most similar command is
        branch

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main|MERGING)
$ git branch --merge
* main

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main|MERGING)
$ git branch --no-merge
  v0.2

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main|MERGING)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main|MERGING)
$ git commit -m "conflictos resueltos"
[main 98607eb] conflictos resueltos

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git merge
Already up to date.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Enumerating objects: 13, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 7 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 781 bytes | 781.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/YuneidisLS/devjumpers.git
   4a55e05..98607eb  main -> main

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git add .

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git commit -m "Se pone nueva linea de comando en el archivo readme"
[main d7f9166] Se pone nueva linea de comando en el archivo readme
 1 file changed, 17 insertions(+), 1 deletion(-)

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 7 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 539 bytes | 539.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/YuneidisLS/devjumpers.git
   98607eb..d7f9166  main -> main

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ ls
1.txt  2.txt  README.md  privada/  privado.txt

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git branch -d v0.2
warning: not deleting branch 'v0.2' that is not yet merged to
         'refs/remotes/origin/v0.2', even though it is merged to HEAD.
error: The branch 'v0.2' is not fully merged.
If you are sure you want to delete it, run 'git branch -D v0.2'.

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git branch -D v0.2
Deleted branch v0.2 (was d3fb05d).

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git log --decorate --oneline
d7f9166 (HEAD -> main, origin/main) Se pone nueva linea de comando en el archivo readme
98607eb conflictos resueltos
d3fb05d se agrefo texto en el archico 1.txt
628df62 Se pone texto en el archivo1.txt
4a55e05 se agrega los nuevos comando en el archico readme
82dc09e (origin/v0.2) Se creaa rama, y ficheros 1.txt,2.txt
cb5dd0d nuevo comando agg en el archico readme.md
bab5ac2 se crea el archico para ignorar la carpeta y archivo privado
dab058e Se crea archivo privado.txt y carpeta privada
be8dd8a se modifica archivo readme
aa554fc commit inicial

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git log --decorate --oneline --graph --all
* d7f9166 (HEAD -> main, origin/main) Se pone nueva linea de comando en el archivo readme
*   98607eb conflictos resueltos
|\
| * d3fb05d se agrefo texto en el archico 1.txt
* | 628df62 Se pone texto en el archivo1.txt
* | 4a55e05 se agrega los nuevos comando en el archico readme
|/
* 82dc09e (origin/v0.2) Se creaa rama, y ficheros 1.txt,2.txt
* cb5dd0d nuevo comando agg en el archico readme.md
* bab5ac2 se crea el archico para ignorar la carpeta y archivo privado
* dab058e Se crea archivo privado.txt y carpeta privada
* be8dd8a se modifica archivo readme
* aa554fc commit inicial

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git list
git: 'list' is not a git command. See 'git --help'.

The most similar commands are
        bisect
        rev-list

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git config --global alias.list

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push
Everything up-to-date

yuneidis.serna_arbus@N-368 MINGW64 ~/Desktop/EjercicioFinal-Git-GitHub/devjumpers (main)
$ git push origin --delete v0.2
To https://github.com/YuneidisLS/devjumpers.git
 - [deleted]         v0.2

