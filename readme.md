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

``` 
## Bundle3 

### Exercise 1

 ```bash
user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$ git commit -m "ths is my team page"
[ft/team-page 39f33d0] ths is my team page
 1 file changed, 11 insertions(+)
 create mode 100644 team.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$
    git push --set-upstream origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 444 bytes | 444.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/mami-now/redo-git-exercises-by-bundles-/pull/new/ft/team-page
remote:
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'
Your branch is up to date with 'origin/ft/team-page'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$ git log
commit 39f33d0ade5c3350a404b3eb2cf0d6475792c3e4 (HEAD -> ft/team-page, origin/ft/team-page)
Author: mamijose <mmammyj@gmail.com>
Date:   Wed Aug 2 12:40:53 2023 +0200

    ths is my team page

commit e1e53074d82236ed91f281c3ceb3aeed5273d51c (origin/main, main, ft/contact-page)
Author: mamijose <mmammyj@gmail.com>
Date:   Tue Aug 1 12:26:45 2023 +0200

    the other change on Readmefile


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/team-page)
$ git checkout  ft/contact-page
Switched to branch 'ft/contact-page'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git cherry-pick 39f33d0ade5c3350a404b3eb2cf0d6475792c3e4
[ft/contact-page a2e2a42] ths is my team page
 Date: Wed Aug 2 12:40:53 2023 +0200
 1 file changed, 11 insertions(+)
 create mode 100644 team.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git commit -m "the contact page is added on"
[ft/contact-page 8e3dce8] the contact page is added on
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git push 
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git push --set-upstream origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 907 bytes | 907.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/mami-now/redo-git-exercises-by-bundles-/pull/new/ft/contact-page
remote:
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
 * [new branch]      ft/contact-page -> ft/contact-page
branch 'ft/contact-page' set up to track 'origin/ft/contact-page'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git commit -m "the faqs page is added on"
[ft/faq-page 5d2d383] the faqs page is added on
 1 file changed, 11 insertions(+)
 create mode 100644 faq.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$  git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 430 bytes | 215.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/mami-now/redo-git-exercises-by-bundles-/pull/new/ft/faq-page
remote:
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
 * [new branch]      ft/faq-page -> ft/faq-page
branch 'ft/faq-page' set up to track 'origin/ft/faq-page'.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git revert 39f33d0ade5c3350a404b3eb2cf0d6475792c3e4
hint: Waiting for your editor to close the file... Vim: Error reading input, exiting...
Vim: Finished.
error: There was a problem with the editor 'vi'.
Please supply the message using either -m or -F option.

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git add .

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git commit -m "the end of bundle3 exercise1 "
[ft/faq-page 9767299] the end of bundle3 exercise1
 1 file changed, 11 deletions(-)
 delete mode 100644 team.html

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 227 bytes | 227.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mami-now/redo-git-exercises-by-bundles-.git
   5d2d383..9767299  ft/faq-page -> ft/faq-page

user@DESKTOP-JN09K5I MINGW64 ~/Desktop/git-exercises%bybundles (ft/faq-page)


  ```