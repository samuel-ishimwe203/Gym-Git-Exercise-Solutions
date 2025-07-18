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

# Bundle 2 exercise 2
=======
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

```

=======
# Bundle 2 Exercise 2

```bash
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git pull origin main
From https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Already up to date.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch ft/service-redesign

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git switch ft/service-redesign
Switched to branch 'ft/service-redesign'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
$ touch service.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
$ git commit -m"service updated"
[ft/service-redesign 64294ad] service updated
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.



user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.71 KiB | 1.71 MiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/service-redesign)
$ git switch main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git commit -m"Their is some changes on service file"
[main d782c45] Their is some changes on service file
 1 file changed, 2 insertions(+)

 user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git commit -m"service changes something"
[main ffadd0c] service changes something
 1 file changed, 16 deletions(-)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git pull
Auto-merging service.html
Merge made by the 'ort' strategy.
 service.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git commit -m"service changes something"
On branch main
Your branch is ahead of 'origin/main' by 5 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git push
Enumerating objects: 18, done.
Counting objects: 100% (17/17), done.
Counting objects: 100% (17/17), done.
Counting objects: 100% (17/17), done.
Counting objects: 100% (17/17), done.
Delta compression using up to 16 threads
Compressing objects: 100% (13/13), done.
Writing objects: 100% (13/13), 1.29 KiB | 1.29 MiB/s, done.
Total 13 (delta 8), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (8/8), completed with 2 local objects.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   3e383b1..1faabb0  main -> main



```


 
# Bundle 2 Exercise 2
```bash
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
### Bandle 3 Exercise 1

```bash


 git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ touch team.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git add .

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git commit -m"team page updated"
[ft/team-page 72baa12] team page updated
 1 file changed, 2 insertions(+), 6 deletions(-)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions/pull/new/ft/team-page
remote:
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/team-page -> ft/team-page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git add README.md

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git commit -m"new changes"
[ft/team-page 1381df7] new changes
 1 file changed, 1 insertion(+), 17 deletions(-)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch ft/contact-page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/service-redesign
  ft/team-page
* main

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git switch ft/team-page 
Switched to branch 'ft/team-page'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git log
commit 1381df74c98bf3dc628ab9e04590461e14a70c5c (HEAD -> ft/team-page)

424c5f5 (HEAD -> ft/contact-page) new changes
aa5bfb6 (origin/main, main) some changes in README.md
1faabb0 Merge branch 'main' of https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions
ffadd0c service changes something
88f8113 service changes something
a11c582 Their is some changes on service file
d782c45 Their is some changes on service file
3e383b1 Merge pull request #3 from samuel-ishimwe203/ft/service-redesign
64294ad service updated
2c9d07e readme changes
5bc8bee changes
2a56ebf Merge pull request #1 from samuel-ishimwe203/dev
517fa9e (origin/dev, dev)  first exercise
ac83d95 updated
ffa99f8 updated
07f17db updated
6884e59 New file again called team
de3d27d They are some changes in about page
ab9c794 The second file is add to my git
3feb14f To rename master branch to main updated

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git switch ft/team-page
Switched to branch 'ft/team-page'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git log --oneline
bd26bbd (HEAD -> ft/team-page) new changes
1381df7 new changes
72baa12 (origin/ft/team-page) team page updated
c9debf9 (origin/ft/service-redesign, ft/service-redesign) new changes
64294ad service updated
2c9d07e readme changes
5bc8bee changes
2a56ebf Merge pull request #1 from samuel-ishimwe203/dev
517fa9e (origin/dev, dev)  first exercise
ac83d95 updated
ffa99f8 updated
07f17db updated
6884e59 New file again called team
de3d27d They are some changes in about page
ab9c794 The second file is add to my git
3feb14f To rename master branch to main updated

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git switch ft/contact-page
Switched to branch 'ft/contact-page'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git cherry-pick bd26bbd
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
error: could not apply bd26bbd... new changes
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config advice.mergeConflict false"

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page|CHERRY-PICKING)
$ git status
On branch ft/contact-page
You are currently cherry-picking commit bd26bbd.
  (fix conflicts and run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page|CHERRY-PICKING)
$ git cherry-pick bd26bbd
error: Cherry-picking is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: cherry-pick failed

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page|CHERRY-PICKING)
$ git add README.md 

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page|CHERRY-PICKING)
$ git commit -m "adding file in REDME.md"
[ft/contact-page 59d118a] adding file in REDME.md
 Date: Thu Jul 17 20:02:28 2025 +0200
 1 file changed, 196 insertions(+), 1 deletion(-)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git add service.html 

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git commit -m "adding line"
[ft/contact-page 5ef936c] adding line
 1 file changed, 1 insertion(+)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git commit -m "adding line"
On branch ft/contact-page
nothing to commit, working tree clean

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/contact-page)
$ git push origin ft/contact-page 
Enumerating objects: 36, done.
Counting objects: 100% (33/33), done.
Delta compression using up to 16 threads
Compressing objects: 100% (26/26), done.
Writing objects: 100% (26/26), 5.01 KiB | 513.00 KiB/s, done.
Total 26 (delta 15), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (15/15), completed with 3 local objects.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
 
 user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git pull origin ft/team-page
From https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions
 * branch            ft/team-page -> FETCH_HEAD
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page|MERGING)
$ git add README.md

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page|MERGING)
$ git commit -m"updation"
[ft/team-page 56a0cf9] updation

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 16 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (10/10), 1.36 KiB | 695.00 KiB/s, done.
Total 10 (delta 7), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (7/7), completed with 3 local objects.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   366d33c..56a0cf9  ft/team-page -> ft/team-page

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$


```
### Bundle 3 Exercise 2

``` bash
user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git add README.md

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git commit -m"some changes on README.md"
[ft/team-page be925c1] some changes on README.md
 1 file changed, 2 insertions(+), 2 deletions(-)

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/team-page)
$ git switch ft/faq-page
Switched to branch 'ft/faq-page'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/faq-page)
$ git branch ft/home-page-redesign

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/faq-page)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git add service.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git commit -m"service changing some changes"
[main 1b17b06] service changing some changes
 1 file changed, 1 insertion(+)


user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git pull origin main
remote: Enumerating objects: 22, done.
remote: Counting objects: 100% (22/22), done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 12 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (12/12), 6.25 KiB | 220.00 KiB/s, done.
From https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
   aa5bfb6..6a5e0af  main       -> origin/main
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main|MERGING)
$ git add service.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main|MERGING)
$ git commit -m"service changing some changes"
[main 21c01ca] service changing some changes

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git pull origin main
From https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Already up to date.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 607 bytes | 607.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (4/4), completed with 3 local objects.
To https://github.com/samuel-ishimwe203/Gym-Git-Exercise-Solutions.git
   6a5e0af..21c01ca  main -> main

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (main)
$ git switch ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/home-page-redesign)
$ git add home.html

user@LAPTOP-7PT2H9GQ MINGW64 ~/Desktop/My folder/Gym-Git-Exercises (ft/home-page-redesign)
$ git commit -m"this is some changes on home page"
[ft/home-page-redesign 6b5ef08] this is some changes on home page
 1 file changed, 1 insertion(+)

user@LAPTOP-7PT2H9GQ MINGW64

```




