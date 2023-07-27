# Git exercises by bundles 
  this is the series of exercises bundle by bundle
   # these are the used commands exercise1 bundle1 and 2
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

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
No local changes to save

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   home.html


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
Saved working directory and index state WIP on dev: be67f69  The commands used through outBundle1&2 of exercise1

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html

no changes added to commit (use "git add" and/or "git commit -a")

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
Saved working directory and index state WIP on dev: be67f69  The commands used through outBundle1&2 of exercise1

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Team.html

nothing added to commit but untracked files present (use "git add" to track)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash
Saved working directory and index state WIP on dev: be67f69  The commands used through outBundle1&2 of exercise1

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash list
stash@{0}: WIP on dev: be67f69 The commands used through outBundle1&2 of exercise1
stash@{1}: WIP on dev: be67f69 The commands used through outBundle1&2 of exercise1
stash@{2}: WIP on dev: be67f69 The commands used through outBundle1&2 of exercise1
stash@{3}: WIP on dev: b573dcf this is about page added on

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Team.html

Dropped refs/stash@{0} (bf9663fc37015adc8c4c8a239091c3a7921d79f2)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash list
stash@{0}: WIP on dev: be67f69 The commands used through outBundle1&2 of exercise1
stash@{1}: WIP on dev: be67f69 The commands used through outBundle1&2 of exercise1
stash@{2}: WIP on dev: b573dcf this is about page added on

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Team.html
        new file:   home.html

Dropped stash@{1} (844b0c2ea11b1ef403cd2e0fe5f87784602e3229)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop stash@{1}^C

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Team.html
        new file:   home.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html

Dropped stash@{0} (51f5ce42de019ed960d8f3ea8e3386d52a28c570)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Team.html
        modified:   about.html
        new file:   home.html
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Team.html

Dropped stash@{0} (015edc9e02e88837996745ea51cfbb6a9aa1b497)

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Team.html
        modified:   about.html
        new file:   home.html
        new file:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Team.html


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git commit -m "this is bundle 2"
[dev 972f62a] this is bundle 2
 4 files changed, 34 insertions(+), 1 deletion(-)
 create mode 100644 Team.html
 create mode 100644 home.html
 create mode 100644 team.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git push
fatal: unable to access 'https://github.com/mami-now/redo-git-exercises-by-bundles-.git/': Recv failure: Connection was reset

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git push
fatal: unable to access 'https://github.com/mami-now/redo-git-exercises-by-bundles-.git/': Recv failure: Connection was reset

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 722 bytes | 722.00 KiB/s, done.
Total 6 (delta 4), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (4/4), completed with 1 local object.
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
   be67f69..972f62a  dev -> dev

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (dev)
$
