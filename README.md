
## The Git & Github Bootcamp



### The Course Curriculum!

- Intro to Git
- Installation
- Git Basics
- Committing In Detail
- Branching
- Merging
- Diffing
- Stashing
- Undoing Changes
- Github Intro
- Fetching & Pulling
- Github Odds & Ends
- Collaborative Workflows
- Rebasing
- Interactive Rebasing
- Git Tags
- Git Behind The Scenes
- Reflogs
- Custom Aliases


### Git Core

- Intro to Git
- Installation
- Git Basics
- Committing In Detail
- Branching
- Merging

### Next Level Git

- Diffing
- Stashing
- Undoing Changes

### Github/Collab Core


- Github Intro
- Fetching & Pulling
- Github Odds & Ends
- Collaborative Workflows

### Git: The other parts

- Rebasing
- Interactive Rebasing
- Git Tags
- Git Behind The Scenes
- Reflogs
- Custom Aliases
## Installation

[Git for Windows](https://git-scm.com/download/win)

[Git for Mac](https://git-scm.com/download/mac)

[Binary installer for Mac](https://sourceforge.net/projects/git-osx-installer/)

[VS Code Installation](https://code.visualstudio.com/download)

[GitKraken](https://www.gitkraken.com/)
## Git Commands!
#### Check your git version
```
git --version
```
### Configuring Git
```
git config --global user.name “[firstname lastname]”
```
##### set a name that is identifiable for credit when review version history
```
git config --global user.email “[valid-email]”
```
##### set an email address that will be associated with each history marker
```
git status
```
git status gives information on the current status of a git repository and its contents
```
git init
```
Use git init to create a new git repository.Before we can do anything git-related, we must initialize a repo first!
```
ls 
```
Lists files and directories in the current directory in a simple format.
```
ls -a 
```
Lists all files and directories, including hidden files that start with a dot.

```
git add <file>
```
Adds a file to the staging area to be included in the next commit.
```
git add .
```
Use git add . to stage all changes at once
```
git commit
```
Records the changes in the repository.
```
git commit -m "your message"
```
Creates a new commit with the staged changes and a descriptive message.
```
git commit -m 'some commit'
git add forgotten_file
git commit --amend
```
Suppose you just made a commit and then realized
you forgot to include a file! Or, maybe you made a
typo in the commit message that you want to
correct.
Rather than making a brand new separate commit,
you can "redo" the previous commit using
the --amend option
```
git branch
```
git branch to view your existing branches
```
git branch <branch-name>
```
make a
new branch based upon the current HEAD
```
git switch <branch-name>
```
```
git checkout <branch-name>
```
Switching Branches
```
git switch -c <branch-name>
```
```
git checkout -b <branch-name>
```
use to switch between branches by creating new branch
```
git branch -d <branch-name>
```
Delete any branch

```
git branch -D <branch-name>

```
forcefully delete a branch

```
git branch -m <new-branch-name>
```
rename a branch 

```
git branch -v
```
Use the -v flag with git branch to view more
information about each branch.
## Exercise

[Committing Basics Exercise](https://plum-poppy-0ea.notion.site/Committing-Basics-Exercise-3dc1ef1873ce45e68cedd2265710d7d8/) : Its a basic assignment on Committing Basics.

[Branching Exercise](https://plum-poppy-0ea.notion.site/Branching-Exercise-b5460c881d56400cb046357d9a430bf8): Its an assignment on Branching

## Authors

- [@AhmadPiracha](https://www.github.com/AhmadPiracha)


## Support

For support, email ahmadpiracha3@gmail.com