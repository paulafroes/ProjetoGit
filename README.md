# ProjetoGit
aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   testededocumentodetexto.txt

no changes added to commit (use "git add" and/or "git commit -a")

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git add .

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git commit -m "modificação feita no arquivo de texto"
[main e69c13d] modificação feita no arquivo de texto
 1 file changed, 1 insertion(+)

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git log
commit e69c13dc2a4bda644049445d28efd514120c2082 (HEAD -> main)
Author: Paula-froes <paula.froes@ymail.com>
Date:   Sun Dec 19 11:26:53 2021 -0300

    modificação feita no arquivo de texto

commit ffbd36634894cb7b8e5f93ba7a05bf7166194a25
Author: Paula-froes <paula.froes@ymail.com>
Date:   Sun Dec 19 11:20:32 2021 -0300

    criação do arquivo de texto

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git remote add origin https://github.com/paulafroes/ProjetoGit.git

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git temote -v
git: 'temote' is not a git command. See 'git --help'.

The most similar command is
        remote

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git remote -v
origin  https://github.com/paulafroes/ProjetoGit.git (fetch)
origin  https://github.com/paulafroes/ProjetoGit.git (push)

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git branch -M main

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$ git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 518 bytes | 103.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/paulafroes/ProjetoGit.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

aplch@DESKTOP-I8S30I2 MINGW64 ~/Desktop/projetogit (main)
$
