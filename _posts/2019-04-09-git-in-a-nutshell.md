---
title:  "Git in a Nutshell"
categories: example
---
# Installation
## Windows

Download and install Git for Windows. Once installed, you’ll be able to use Git from the command prompt or PowerShell.

Git for Windows does not automatically update. Update it by downloading the newer version of it.

## macOS

Install Homebrew and run the following to install an up to date version of Git on your Mac:

> brew install git

To update your Git install, use Homebrew’s upgrade option:

> brew upgrade git

## Linux

Use your Linux package management system to install Git. on Ubuntu:

```
sudo apt-get install git
```
## Configure Git

Run the following commands from the command prompt after installing Git to configure this information:

```
git config --global user.name "user name"

git config --global user.email "user email"
```
## Git Commands

Use the git init command to create a new repo from an existing folder on your computer. From the command line, navigate to the root folder containing your code and run

```
git init
```

with git add . move changes from the working directory to the staging area.

```
git add .
```

git commit Takes the staged files and commits it to the project history. Together with git add, this saves your changes in the main repo.

```
git commit -m "commit message"
```

Use the git clone command to copy the contents of an existing repo to a folder on your computer. From the command line, navigate to the folder you want to contain the cloned repo, then run:

```
git clone (URL of the repo)
```

create branches using the git branch command:

```
git branch <branchname>
```

Use the git push to save your changes on the server.

```
git push origin <branchname>
```

To keep the local repository in sync with the remote repository

```
git pull origin master
```

The above are just a handfull of commands that can be used.
