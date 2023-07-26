# Git exercises by bundles 
  this is the series of exercises bundle by bundle
   # these are the used commands 
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        about.html

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git commit -m "this is about page added on"
[dev b573dcf] this is about page added on
 1 file changed, 11 insertions(+)
 create mode 100644 about.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git  push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 463 bytes | 463.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
   350898b..b573dcf  dev -> dev

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
No local changes to save

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
No local changes to save

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
Saved working directory and index state WIP on dev: b573dcf this is about page added on

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git checkout test
Switched to a new branch 'test'
branch 'test' set up to track 'origin/test'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (test)
$ git branch --delete test
error: Cannot delete branch 'test' checked out at 'C:/Users/user/Desktop/git-exercises%bybundles'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (test)
$ git push origin test
Everything up-to-date

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (test)
$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git branch --delete test
Deleted branch test (was f7937bb).

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop team.html
error: team.html is not a valid reference

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop team.html
error: team.html is not a valid reference

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git push origin --delete test
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
 - [deleted]         test

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git commit -m "the tittle change"
[dev 4a5b6a0] the tittle change
 2 files changed, 2 insertions(+), 2 deletions(-)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git commit
On branch dev
Your branch is ahead of 'origin/dev' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$
 *  History restored 


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)