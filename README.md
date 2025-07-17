# Git Exercises project
This project will be used for many git exercises

## Bandle 1
  # Exercise 1

``` bash
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises
$ git init
Initialized empty Git repository in C:/Users/user/Desktop/My folder/Gym-Git-Exercises/.git/

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (master)
$ touch index.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (master)
$ git checkout -b main
Switched to a new branch 'main'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch -m main master

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (master)
$ git branch -m master main

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git commit -m"To rename master branch to main updated"
[main (root-commit) 3feb14f] To rename master branch to main updated
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git log --oneline
3feb14f (HEAD -> main) To rename master branch to main updated


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git remote add origin https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)

$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 234 bytes | 234.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git push
Everything up-to-date

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git remote -v
origin  https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git (push)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch dev

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git checkout dev
Switched to branch 'dev'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git branch test

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git branch
* dev
  main
  test

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout test
Switched to branch 'test'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (test)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git checkout dev
Switched to branch 'dev'




user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises ((3feb14f...))
$ git checkout dev
Switched to branch 'dev'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git branch -d test
Deleted branch test (was 3feb14f).

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git branch
* dev
  main
## Exercise 2

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ touch home.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m"The second file is add to my git"
[dev ab9c794] The second file is add to my git
 1 file changed, 13 insertions(+)
 create mode 100644 home.html


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 447 bytes | 447.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ touch about.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m"They are some changes in about page"
[dev de3d27d] They are some changes in about page
 1 file changed, 11 insertions(+)
 create mode 100644 about.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev 
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 494 bytes | 494.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   ab9c794..de3d27d  dev -> dev
branch 'dev' set up to track 'origin/dev'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push
Everything up-to-date

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev 
branch 'dev' set up to track 'origin/dev'.
Everything up-to-date

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: de3d27d They are some changes in about page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ touch team.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m"New file again called team"
[dev 6884e59] New file again called team
 1 file changed, 11 insertions(+)
 create mode 100644 team.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 450 bytes | 450.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   de3d27d..6884e59  dev -> dev
branch 'dev' set up to track 'origin/dev'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push
Everything up-to-date


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m"updated"
[dev 07f17db] updated
 1 file changed, 3 insertions(+)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 346 bytes | 346.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   6884e59..07f17db  dev -> dev
branch 'dev' set up to track 'origin/dev'.


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev
branch 'dev' set up to track 'origin/dev'.
Everything up-to-date

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 07f17db updated

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add team.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 07f17db updated

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m"updated"
[dev ffa99f8] updated
 1 file changed, 4 insertions(+)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push -u origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 293 bytes | 293.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   07f17db..ffa99f8  dev -> dev
branch 'dev' set up to track 'origin/dev'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push
Everything up-to-date

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m"updated "
[dev ac83d95] updated
 1 file changed, 1 insertion(+)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git branch
* dev
  main


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git log --oneline
ac83d95 (HEAD -> dev) updated
ffa99f8 (origin/dev) updated
07f17db updated
6884e59 New file again called team
de3d27d They are some changes in about page
ab9c794 The second file is add to my git
3feb14f (origin/main, main) To rename master branch to main updated


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git reset

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ rm team.html
```

## Bundle 2
#  Exercise 1 

 ```bash

 user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ touch services.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$



user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ touch services.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ touch services.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout -b ft/bundle-2
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ touch services.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git checkout dev
Switched to branch 'dev'
Your branch is ahead of 'origin/dev' by 1 commit.
  (use "git push" to publish your local commits)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git commit -m" first exercise"
[dev 517fa9e]  first exercise
 2 files changed, 323 insertions(+)
 create mode 100644 README.md
 create mode 100644 services.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (7/7), 2.20 KiB | 1.10 MiB/s, done.
Total 7 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   ffa99f8..517fa9e  dev -> dev

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   ffa99f8..517fa9e  dev -> dev

To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   ffa99f8..517fa9e  dev -> dev
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   ffa99f8..517fa9e  dev -> dev


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout ft/bundle-2
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git stash list
stash@{0}: WIP on dev: 07f17db updated
stash@{1}: WIP on dev: 07f17db updated
stash@{2}: WIP on dev: de3d27d They are some changes in about page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git stash@{0}
git: 'stash@{0}' is not a git command. See 'git --help'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git stash pop stash@{0}
Auto-merging team.html
CONFLICT (content): Merge conflict in team.html
On branch ft/bundle-2
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both modified:   team.html

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git checkout dev
team.html: needs merge
error: you need to resolve your current index first

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git checkout dev
team.html: needs merge
error: you need to resolve your current index first

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git switch dev
team.html: needs merge
error: you need to resolve your current index first

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git reset
Unstaged changes after reset:
M       team.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git switch dev
M       team.html
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git stash list
stash@{0}: WIP on dev: 07f17db updated
stash@{1}: WIP on dev: 07f17db updated
stash@{2}: WIP on dev: de3d27d They are some changes in about page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git add README.md

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git stash
Saved working directory and index state WIP on dev: 517fa9e  first exercise

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (dev)
$ git switch ft/bundle-2
Switched to branch 'ft/bundle-2'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git stash list
stash@{0}: WIP on dev: 517fa9e first exercise
stash@{1}: WIP on dev: 07f17db updated
stash@{2}: WIP on dev: 07f17db updated
stash@{3}: WIP on dev: de3d27d They are some changes in about page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/bundle-2)
$ git stash pop stash@{3}
On branch ft/bundle-2
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped stash@{3} (9ecb06c16c8545f788e3b35b8c87e45fb733efdc)


```
## Bundle 2
# Exercise 2

```bash
$ git diff main --oneline
diff --git a/README.md b/README.md
index 352c80a..bfd5938 100644
--- a/README.md
+++ b/README.md
@@ -508,115 +508,4 @@ Dropped stash@{3} (9ecb06c16c8545f788e3b35b8c87e45fb733efdc)


 ```
-# Bundle 2 Exercise 2
-```bash
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git pull origin main
-From https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions
- * branch            main       -> FETCH_HEAD
-Already up to date.
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git branch ft/service-redesign
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git switch ft/service-redesign
-Switched to branch 'ft/service-redesign'
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
-$ touch service.html
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
-$ git add .
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
-$ git commit -m"service updated"
-[ft/service-redesign 64294ad] service updated
- 1 file changed, 12 insertions(+)
- create mode 100644 service.html
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
-$ git push
-fatal: The current branch ft/service-redesign has no upstream branch.
-To push the current branch and set the remote as upstream, use
-
-    git push --set-upstream origin ft/service-redesign
-
-To have this happen automatically for branches without a tracking
-upstream, see 'push.autoSetupRemote' in 'git help config'.
-
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
-$ git push origin ft/service-redesign
-Enumerating objects: 8, done.
-Counting objects: 100% (8/8), done.
-Delta compression using up to 16 threads
-Compressing objects: 100% (6/6), done.
-Writing objects: 100% (6/6), 1.71 KiB | 1.71 MiB/s, done.
-Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
-remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
-remote:
-remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
-remote:      https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
-remote:
-To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
- * [new branch]      ft/service-redesign -> ft/service-redesign
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
-$ git switch main
-Switched to branch 'main'
-Your branch is ahead of 'origin/main' by 1 commit.
-  (use "git push" to publish your local commits)
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git add .
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git commit -m"Their is some changes on service file"
-[main d782c45] Their is some changes on service file
- 1 file changed, 2 insertions(+)
-
- user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git add .
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git commit -m"service changes something"
-[main ffadd0c] service changes something
- 1 file changed, 16 deletions(-)
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git pull
-Auto-merging service.html
-Merge made by the 'ort' strategy.
- service.html | 12 ++++++++++++
- 1 file changed, 12 insertions(+)
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git add .
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git commit -m"service changes something"
-On branch main
-Your branch is ahead of 'origin/main' by 5 commits.
-  (use "git push" to publish your local commits)
-
-nothing to commit, working tree clean
-
-user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
-$ git push
-Enumerating objects: 18, done.
-Counting objects: 100% (17/17), done.
-Counting objects: 100% (17/17), done.
-Counting objects: 100% (17/17), done.
-Counting objects: 100% (17/17), done.
-Delta compression using up to 16 threads
-Compressing objects: 100% (13/13), done.
-Writing objects: 100% (13/13), 1.29 KiB | 1.29 MiB/s, done.
-Total 13 (delta 8), reused 0 (delta 0), pack-reused 0 (from 0)
-remote: Resolving deltas: 100% (8/8), completed with 2 local objects.
-To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
-   3e383b1..1faabb0  main -> main
-
-

-```
\ No newline at end of file
diff --git a/services.html b/services.html
index f7106a1..10fdef3 100644
--- a/services.html
+++ b/services.html
@@ -8,8 +8,6 @@
 <body>

     <h2>servise page</h2>
-    <h4>My name is samuel</h4>
-    <h4>From Nyagatare</h4>

 </body>
 </html>
\ No newline at end of file
(END)
```

