## understand the basics

* `git help`: display manpage for command or topic
* `git init`: initialize a new git repository
* `git config`: set configuration options, per-repository or globally
* `git add`: move changes from working directory to staging area
* `git commit`: make a snapshot of the repository, committing changes from the staging area
* `git status`: display state of working and staging areas
* `git diff`: show changes between working directory and staging area
* `git stash`: move working directory changes to a tracked, temporary space

## view project history

* `git show`: display the most recent commit details and message
* `git log`: display all snapshots (commits) of previous revisions of the project
* `git reflog`: display all previous references pointed at by HEAD
* `git blame`: display line-by-line author and commit details for a file

## undo your changes

* `git revert`: undo a commit by applying the inverse of its changes
* `git reset`: undo local changes, in staging or working areas

## work with branches

* `git branch`: list local branches or create a new one referencing the current commit
* `git checkout`: switch current branch, or change files in working directory to their state in a branch
* `git merge`: integrate changes from another branch into current branch
* `git tag`: like a branch, but pinned to a commit

## work with others

* `git clone`: copy a git repository from an upstream source (github.com, another developer, etc)
* `git remote`: manage (ie: add, rename, delete) references to remote repositories
* `git push`: send your local changes to an upstream repository
* `git fetch`: download history from an upstream repository, but do not integrate it locally
* `git pull`: as with fetch, but also merge changes into your current branch

## advanced

* `git rebase`: move commits to the tip of another branch

## further reading

* https://try.github.io/
* https://www.atlassian.com/git/
* https://www.atlassian.com/git/glossary
* https://www.git-tower.com/blog/git-cheat-sheet/
* https://eev.ee/blog/2015/04/24/just-enough-git-to-be-less-dangerous/
* https://raw.githubusercontent.com/hbons/git-cheat-sheet/master/preview.png
