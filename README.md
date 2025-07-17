# git-practice
## Bundle 1
### Exercise 1
```bash

On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
t add" to track)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (master)   
$ ls
index.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (master)   
$ it add index.html
bash: it: command not found

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (master)
$ git add index.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (master)   
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (master)
$ git branch -m master main

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "my first commit new file"
[main (root-commit) f9501d8] my first commit new file
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git remote add origin https://github.com/Olivier-Masabo/git-practice.git

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/Olivier-Masabo/git-practice.git/': Could not resolve host: github.com

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/Olivier-Masabo/git-practice.git/': Recv failure: Connection was reset

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/Olivier-Masabo/git-practice.git/': Recv failure: Connection was reset

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/Olivier-Masabo/git-practice.git/': Could not resolve host: github.com

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$





    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/Olivier-Masabo/git-practice.git/': Could not resolve host: github.com
    git push --set-upstream origin main
    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/Olivier-Masabo/git-practice.git/': Could not resolve host: github.com

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push -u origin main
To https://github.com/Olivier-Masabo/git-practice.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/Olivier-Masabo/git-practice.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git pull origin main
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 1.50 KiB | 16.00 KiB/s, done.
From https://github.com/Olivier-Masabo/git-practice
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$  git pull origin main --allow-unrelated-histories
From https://github.com/Olivier-Masabo/git-practice
 * branch            main       -> FETCH_HEAD
Merge made by the 'ort' strategy.
 LICENSE   | 21 +++++++++++++++++++++
 README.md |  1 +
 2 files changed, 22 insertions(+)
 create mode 100644 LICENSE
 create mode 100644 README.md

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Olivier-Masabo/git-practice.git
   2ca13ca..280769b  main -> main
branch 'main' set up to track 'origin/main'.

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git branch dev

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git checkout dev
Switched to branch 'dev'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$ git branch test

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$ git checkout test
Switched to branch 'test'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (test)
$ git checkout dev
Switched to branch 'dev'


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$ git checkout test
Switched to branch 'test'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (test)
$ git checkout dev
Switched to branch 'dev'

$ git checkout test
Switched to branch 'test'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (test)
$ git checkout dev
Switched to branch 'dev'


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (test)
$ git checkout dev
Switched to branch 'dev'

$ git checkout dev
Switched to branch 'dev'


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$ git branch -d test
Deleted branch test (was 280769b).

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$ git branch
* dev
  main

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$ git branch -r
  origin/HEAD -> origin/main
  origin/main

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (dev)
$
```

## Bundle 1
### Exercise 2

```bash
Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git add home.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash
Saved working directory and index state WIP on main: 2d65a0f adding  README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash list
stash@{0}: WIP on main: 2d65a0f adding README

Writing objects: 100% (3/3), 1.78 KiB | 303.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Olivier-Masabo/git-practice.git
   280769b..2d65a0f  main -> main

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git add home.html
$ git add home.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)     
$ git stash
Saved working directory and index state WIP on main: 2d65a0f adding  README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)     
$ git stash list
stash@{0}: WIP on main: 2d65a0f adding README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)     
$ git add about.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash
Saved working directory and index state WIP on main: 2d65a0f adding  README

$ git stash list
stash@{0}: WIP on main: 2d65a0f adding README
stash@{1}: WIP on main: 2d65a0f adding README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git add team.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash
Saved working directory and index state WIP on main: 2d65a0f adding  README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash list
stash@{0}: WIP on main: 2d65a0f adding README
stash@{1}: WIP on main: 2d65a0f adding README
stash@{2}: WIP on main: 2d65a0f adding README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (97ad845b45e65c0330d5ad069cdc470000667c77)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash list
stash@{0}: WIP on main: 2d65a0f adding README
stash@{1}: WIP on main: 2d65a0f adding README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (c47863299fa811bdbd50a3b4f122cd8a74a6e20b)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git add --all

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "setup home and about page"
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "setup home and about page"
        new file:   about.html
        new file:   home.html


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "setup home and about page"

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "setup home and about page"
Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "setup home and about page"
[main 4527b0e] setup home and about page
 2 files changed, 22 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 615 bytes | 205.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
To https://github.com/Olivier-Masabo/git-practice.git
   2d65a0f..4527b0e  main -> main

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash list
stash@{0}: WIP on main: 2d65a0f adding README

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash pop stash@{0}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (b49abcf1c370de4c3f62ecd9b370ed292396e7b4)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git reset

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git stash reset
fatal: subcommand wasn't specified; 'push' can't be assumed due to unexpected token 'reset'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git reset

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$
```