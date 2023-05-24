# Hello World
Just a sample repo to get familiar wuth github

plus It's also fun to re-write the  old 'Hello World' code.

If you are checking my github to assess my coding skills, please dont put this directory in account.

BTW happy to start working with GitHub.

## things I did by now
1. created a new repository on GitHub using new.
2. used add file => create new file to create a markdown file
3. did some changes to check the changes using the commits option
4. used add file => upload files to add my python file to the repo
5. used git clone to clone + URL to clone the repo on my local machine to be able to modify it localy
6. used git status to see the status of the files that where modified but not commited
7. used git add command  to make git track the newly added, modified or deleted files which are not tracked by the git repo
8. used git commit -m "sample massage" to commit the changes into the repo

## push
we use git push to a live repository where the project is hosted

in order to do that we need permission, and we use SSH keys to do that.

1. use ssh-keygen -t rsa -b 'strength' -C "email" to create an SSH key
2. name your key
3. optionally add a passphrase to your key
4. search for it using ls | grep shatelpckey
5. get the .pub key and go to GitHub setting => SSH and GPG keys => new SSH key and add your key
6. now we can use the push command git push origin 'branch'
