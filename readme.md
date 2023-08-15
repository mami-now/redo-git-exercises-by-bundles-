# Git exercises by bundles 
  this is the series of exercises bundle by bundle
 
  # Bundle2 exercise2

 ``` bash user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git pop stash service.html
git: 'pop' is not a git command. See 'git --help'.

The most similar command is
        log

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git stash apply
No stash entries found.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git stash list

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash list

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git checkout ft/bundle2
error: pathspec 'ft/bundle2' did not match any file(s) known to git

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git checkout  ft/bundle-2
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout Dev
Switched to branch 'Dev'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (Dev)
$ git checkout  ft/bundle-2
Switched to branch 'ft/bundle-2'
Your branch is up to date with 'origin/ft/bundle-2'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git pull
Already up to date.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout -b ft/service-redesign
fatal: a branch named 'ft/service-redesign' already exists

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout  ft/service-redesign
Switched to branch 'ft/service-redesign'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git pull
Already up to date.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout  ft/service-redesign
Switched to branch 'ft/service-redesign'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git status
On branch ft/service-redesign
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   services.html


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git commit -m " this is the additional file inside ft branch"
[ft/service-redesign f56f3bd]  this is the additional file inside ft branch
 1 file changed, 13 insertions(+)
 create mode 100644 services.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$   git push --set-upstream origin ft/service-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 509 bytes | 254.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/mami-now/redo-git-exercises-by-bundles-/pull/new/ft/service-redesign
remote:
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$   git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git merge ft/service-redesign 
Updating f7937bb..f56f3bd
Fast-forward
 services.html | 13 +++++++++++++
 1 file changed, 13 insertions(+)
 create mode 100644 services.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git commit -m  
error: switch 'm' requires a value

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git commit -m  "this is the other change "
[main 95ccbab] this is the other change
 1 file changed, 1 insertion(+)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 322 bytes | 322.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
   f7937bb..95ccbab  main -> main

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ gi checkout ft/service-redesign
bash: gi: command not found

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git pull
Already up to date.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git merge main
Updating f56f3bd..95ccbab
Fast-forward
 services.html | 1 +
 1 file changed, 1 insertion(+)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$
```
## Bundle4 - exercise1
```bash

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote add git_copy https://github.com/mami-now/git-exercises-clone-.git

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote
git_copy
origin

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git commit -m "feature added from home page"
[main a5ad70e] feature added from home page
 1 file changed, 1 insertion(+)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 380 bytes | 380.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
   e2206b7..a5ad70e  main -> main

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git commit -m "this is the new changes  on home page "
[main 02f01bf] this is the new changes  on home page
 1 file changed, 1 insertion(+), 1 deletion(-)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push orgin
fatal: 'orgin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 387 bytes | 387.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
   a5ad70e..02f01bf  main -> main

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remoted origin https://github.com/mami-now/git-exercises-clone-.git
git: 'remoted' is not a git command. See 'git --help'.

The most similar command is
        remote-fd

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push origin
Everything up-to-date

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push copy-origin
fatal: 'copy-origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push git-copy
fatal: 'git-copy' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote add git-copy https://github.com/mami-now/git-exercises-clone-.git

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote add git-copy https://github.com/mami-now/git-exercises-clone-.git
error: remote git-copy already exists.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push git-copy
Enumerating objects: 27, done.
Counting objects: 100% (27/27), done.
Delta compression using up to 4 threads
Compressing objects: 100% (26/26), done.
Writing objects: 100% (27/27), 4.07 KiB | 1.35 MiB/s, done.
Total 27 (delta 8), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (8/8), done.
To https://github.com/mami-now/git-exercises-clone-.git
 * [new branch]      main -> main

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git push git_copy
Everything up-to-date

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote -v
git-copy        https://github.com/mami-now/git-exercises-clone-.git (fetch)
git-copy        https://github.com/mami-now/git-exercises-clone-.git (push)
git_copy        https://github.com/mami-now/git-exercises-clone-.git (fetch)
git_copy        https://github.com/mami-now/git-exercises-clone-.git (push)
origin  https://github.com/mami-now/redo-git-exercises-by-bundles-.git (fetch)
origin  https://github.com/mami-now/redo-git-exercises-by-bundles-.git (push)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote rm git-copy 

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git -v
git version 2.40.1.windows.1

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git remote -v
git_copy        https://github.com/mami-now/git-exercises-clone-.git (fetch)
git_copy        https://github.com/mami-now/git-exercises-clone-.git (push)
origin  https://github.com/mami-now/redo-git-exercises-by-bundles-.git (fetch)
origin  https://github.com/mami-now/redo-git-exercises-by-bundles-.git (push)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$


 ```