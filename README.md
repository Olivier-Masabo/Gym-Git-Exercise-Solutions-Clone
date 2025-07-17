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

## Bundle 2
### exercise 1

```bash
Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/bundle-2)
$ git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html
        team.html

nothing added to commit but untracked files present (use "git add" to track)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/bundle-2)
$ git add services.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/bundle-2)
$ git status
On branch ft/bundle-2
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   services.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/bundle-2)
$ git commit -m "add service page"
[ft/bundle-2 417fe41] add service page
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 461 bytes | 461.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/Olivier-Masabo/git-practice.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/bundle-2)
$
```

## Bundle 2
### Exercise 2
```bash

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 880 bytes | 67.00 KiB/s, done.
From https://github.com/Olivier-Masabo/git-practice
   182f501..076db84  main       -> origin/main
Updating 182f501..076db84
Fast-forward
 services.html | 11 +++++++++++
 1 file changed, 11 insertions(+)
 create mode 100644 services.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git add .

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git commit -m "made some changes"
[ft/service-redesign 3d496a7] made some changes
 2 files changed, 12 insertions(+)
 create mode 100644 team.html

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$  git push --set-upstream origin ft/service-redesign
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 433 bytes | 216.00 KiB/s, done.
Total 4 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/Olivier-Masabo/git-practice.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git add .

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "making some changes in service page"
[main 007c069] making some changes in service page
 1 file changed, 1 insertion(+)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 345 bytes | 172.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
$ git add .

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git commit -m "making some changes in service page"
[main 007c069] making some changes in service page
 1 file changed, 1 insertion(+)

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 345 bytes | 172.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 345 bytes | 172.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
To https://github.com/Olivier-Masabo/git-practice.git
   076db84..007c069  main -> main

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git diff ft/service-redesign  main
diff --git a/services.html b/services.html
index 4343ea9..b613bec 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
diff --git a/services.html b/services.html
index 4343ea9..b613bec 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
  </head>
  <body>
     <h1>these are our sevices</h1>
-    <h1>Welcome back</h1>
+    <h2>web development</h2>
  </body>
  </html>
\ No newline at end of file
diff --git a/team.html b/team.html
deleted file mode 100644
index 11a34ab..0000000
@@ -1,11 +0,0 @@
-  <!DOCTYPE html>
- <html lang="en">
:...skipping...
diff --git a/services.html b/services.html
index 4343ea9..b613bec 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
  </head>
  <body>
     <h1>these are our sevices</h1>
-    <h1>Welcome back</h1>
+    <h2>web development</h2>
  </body>
  </html>
\ No newline at end of file
diff --git a/team.html b/team.html
deleted file mode 100644
index 11a34ab..0000000
--- a/team.html
+++ /dev/null
@@ -1,11 +0,0 @@
-  <!DOCTYPE html>
- <html lang="en">
- <head>
-    <meta charset="UTF-8">
-    <meta name="viewport" content="width=device-width, initial-scale=1.0">
-    <title>Git exercise | team</title>
- </head>
- <body>
-    <h1>welcome to team page</h1>
:...skipping...
diff --git a/services.html b/services.html
index 4343ea9..b613bec 100644
--- a/services.html
+++ b/services.html
@@ -7,6 +7,6 @@
  </head>
  <body>
     <h1>these are our sevices</h1>
-    <h1>Welcome back</h1>
+    <h2>web development</h2>
  </body>
  </html>
\ No newline at end of file
diff --git a/team.html b/team.html
deleted file mode 100644
index 11a34ab..0000000
--- a/team.html
+++ /dev/null
@@ -1,11 +0,0 @@
-  <!DOCTYPE html>
- <html lang="en">
- <head>
-    <meta charset="UTF-8">
-    <meta name="viewport" content="width=device-width, initial-scale=1.0">
-    <title>Git exercise | team</title>
- </head>
- <body>
-    <h1>welcome to team page</h1>
- </body>
- </html>

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

+++ /dev/null
@@ -1,11 +0,0 @@
-  <!DOCTYPE html>
- <html lang="en">
- <head>
-    <meta charset="UTF-8">
-    <meta name="viewport" content="width=device-width, initial-scale=1.0">
-    <title>Git exercise | team</title>
- </head>
- <body>
-    <h1>welcome to team page</h1>
- </body>
- </html>

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.

CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.


Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign|MERGING)
$

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign|MERGING)
$

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign|MERGING)
Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign|MERGING)
$ git add .

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign|MERGING)
$ git commit -m "mergin main with ft/service-redesign"
[ft/service-redesign 67b1d25] mergin main with ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 312 bytes | 104.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
To https://github.com/Olivier-Masabo/git-practice.git
[ft/service-redesign 67b1d25] mergin main with ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 312 bytes | 104.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
To https://github.com/Olivier-Masabo/git-practice.git
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: This repository moved. Please use the new location:
remote:   https://github.com/Olivier-Masabo/Gym-Git-Exercise-Solutions.git
To https://github.com/Olivier-Masabo/git-practice.git
To https://github.com/Olivier-Masabo/git-practice.git
   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$

   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$

   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign
   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$

   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$


   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign
   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$


   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$


   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign
   3d496a7..67b1d25  ft/service-redesign -> ft/service-redesign

Tech Heaven Shop@Mufasa MINGW64 ~/myProject (ft/service-redesign)
$
```
