# learning git

Git is an awesome tool however it was written by a madman, who thinks that software should be as clever and powerful as it's creator, and since no one is as powerful or clever as Linus, it can be an incredibly painful experience for us mere mortals.

## Pull and Merge do NOT exist... there is no spoon

Using git pull or git merge is not something that a nomrmal git user should be using, because it it creates affitional noise in the git log, creating 'merge bubbles' where none are needed, essentially creating extra git commits that provide absolutely no value, and make working with other people next to impossible.

## Introducing git fetch and git rebase.....

First in order to use a git fetch or a git rebase we need to have a remote for our repository, and we will be using github. We will also need to push up a change in a non-master branch to create a pull request from.

~~~ bash
git remote add origin git@github.com:torresga/learning-git.git
~~~

