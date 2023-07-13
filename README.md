
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
## Git Commands!

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