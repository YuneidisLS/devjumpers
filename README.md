
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



