# Git and version control

## What is Git?
Git is a Distributed Version Control systems (DVCS) Developed in 2005 by Linus Torvalds, chief architect of Linux.

Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows. In contast to older Centraliized Version Control Systems (CVCS) These multiple mirrored repositories also reduce the risk of catastrophic data loss. 

## GitHub

GitHub is a hub-focused tool which facilitates Integration-Manager Workflow. It is the largest existing host for Git repositories and is used by millions of developers worldwide. A high percentage of Git repositories reside on GitHub, and this resource is used by many open source projects.


## GIT commands

* git init Initializes a git repository locally
* git add filename Adds a single named file/folder to be tracked
* git add . Adds all folders in current dierectory.
* git commit *Commits tracked changes to the repository, add -m 'Your message here' to add a message to a commit. 
  Messages should show ***why*** you are commiting changes.
* git push pushes changes from your local directory to the remote directory.
* git pull pulls and merges changes from remote to local.
* git clone clones a remote directory to your local machine.

## Cloning from git hub to local directory

You can create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

> `$ git clone https://github.com/test`

To clone a repository into a directory with another name of your choosing, use the following command format:

> `$ git clone https://github.com/test mydirectory`

## pushing files from local directory

To sync files from a local directory to GitHub

1. > `git add .`
2. > `git commit`
3. > `git push`