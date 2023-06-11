# Hello World
Just a sample repo to get familiar with GitHub

plus It's also fun to re-write the  old 'Hello World' code.

If you are checking my GitHub to assess my coding skills, please don't put this directory in account.

BTW happy to start working with GitHub.

## GitHUB commands
1. created a new repository on GitHub using new.
2. use add file => create new file to create a markdown file
3. make some changes to check the changes using the commits option
4. use add file => upload files to add my python file to the repo
5. use git clone to clone + URL to clone the repo on my local machine to be able to modify it locally
6. use git status to see the status of the files that where modified but not committed
7. use git add command  to make git track the newly added, modified or deleted files which are not tracked by the git repo
8. use git commit -m "sample massage" to commit the changes into the repo

## push
we use git push to a live repository where the project is hosted

in order to do that we need permission, and we use SSH keys to do that.

1. use ssh-keygen -t rsa -b 'strength' -C "email" to create an SSH key
2. name your key
3. optionally add a passphrase to your key
4. search for it using ls | grep shatelpckey
5. get the .pub key and go to GitHub setting => SSH and GPG keys => new SSH key and add your key
6. now we can use the push command git push origin 'branch'


## creating a local repo and push
1. create a project directory (folder)
2. use cd to go to the directory
3. use git init command to initialize git in the directory
4. add and commit your new files
5. create a new repo on GitHub then copy the link and use git remote add origin 'link'
6. you can check it using git remote -v
7. then push your commits


## GitHub Workflow
1. write code
2. commit changes using commit and add message and description
3. Make a Pull request

## Local Git Workflow
1. write code
2. make Changes
3. (git status) git add
4. git commit
5. git push
6. Make a Pull request

## Git Branching
branching is used to change your code in a sandbox environment

then when it's done we can merge it back to your main branch

hotfix branch is a branch of code that is made for a quick change or a quick bug fix
1. use git branch command to check the branches we have already
2. use git checkout -b 'name' to create a new branch
3. git checkout 'name' is used to move between branches

for example this text was added in the 'addtext branch'

4. now we can merge the branches into the main branch
5. but  first we may want to compare the files using git diff 'other branch name' command
6. we can use git merge but the more common way is to use pull requests

A pull request is when we want to pull our code into the main branch from the feature branch

so when we make a pull request we can still make changes and comments but when the merge is complete our feature branch is destroyed

7. Write a pretty good comment
8. then merge the pull request
9. after that we need to pull down the changes from GitHub into our local machine using git pull origin 'branch name'
10. delete the feature branch using git branch -d 'branch name'
11. to keep up to date with main (master) branch, use git merge main on the feature branch
12. we may face conflicts that we can fix in the IDE or any other place like GITHUB

* you can use git rm filename to remove a file from your git repo

## undoing in GIT
1. we can undo our changes on GIT if me made a mistake
2. we can easily undo with git rest filename
3. if you want to undo the last commit use git reset HEAD
4. use git reset --hard (head/commit code) to completely wipe the changes

## Forking
1. Forking means to copy a whole repository in order to gain access, make changes and moe
2. to fork we use the fork key in the GitHub interface
3. after the forking is complete its basically another repository in your library where you can do anything you want to it
* you probably don't want to fork your own code, because you already have everything you want here

##Extras
1. git log --oneline gives you a summurized log of commits
2. git revert commit code makes you go back to a certain commit
