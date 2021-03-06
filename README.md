# git_training
Team git training

## Benefits of git
Git allows two main things: 
- version control
- collaboration

## Donwload
You can donwload git from the [official site](https://git-scm.com/downloads)

(Windows)I recommend downloading [Cmder](https://cmder.net/) a pretty cmd environment that already has git included

## Setting up git

After installation, type the following in a cmd console using your own credentials:

```
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

source: https://git-scm.com/book/en/v1/Getting-Started-First-Time-Git-Setup#Your-Identity

If you  want to avoid typing your username and password every time, follow the instructions in [this link](https://help.github.com/en/articles/caching-your-github-password-in-git)

## Downloading training repo

Before, two definitions: 

**clone**: This will create a local copy of the repository you want to work with. Every change (push) that you make will contribute to the original project

**fork**: This will copy an existing repository into your own github profile. When you update files (push) you will NOT contribute to the original project, but to your own.

### Instructions
1. go to: https://github.com/JorgeOrozcoP/git_training

2. Press the green button that says "Clone or download" and copy the link shown

3. Create a folder to host your git projects `mkdir git/`

4. Navigate to that folder and use the command `git clone` followed by the link that you copied earlier. For this exercise, the complete command is: `git clone https://github.com/JorgeOrozcoP/git_training.git`

## Basic command flow: creating a branch

`git checkout -b new-feature upper-branch` use this to create a branch and immediately switch to it, copying the upper branch

## Basic command flow: commiting a change

`git status` will show the current status of files 

`git diff` check the modifications just done to your files

`git add [file path]` will stage a file to be commited

`git add --all` will stage all modified files to be commited

`git commit -m "some message"` will commit the staged files. Think of a commit as a 'timestamp'. The staged files will be commited to a specific point in time

`git pull origin branch-name` before you upload your changes (push) make sure that your branch is up to date 

`git push origin branch-name` upload (push) your changes into the repository




