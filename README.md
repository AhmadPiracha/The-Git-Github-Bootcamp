# The Git & GitHub Bootcamp

## Course Curriculum

### Git Core

- [Intro to Git](#intro-to-git)
- [Installation](#installation)
- [Git Basics](#git-basics)
- [Committing In Detail](#committing-in-detail)
- [Branching](#branching)
- [Merging](#merging)

### Next Level Git

- [Diffing](#diffing)
- [Stashing](#stashing)
- [Undoing Changes](#undoing-changes)

### Github/Collab Core

- [Github Intro](#github-intro)
- [Fetching & Pulling](#fetching-and-pulling)
- [Github Odds & Ends](#github-odds-and-ends)
- [Collaborative Workflows](#collaborative-workflows)

### Git: The Other Parts

- [Rebasing](#rebasing)
- [Interactive Rebasing](#interactive-rebasing)
- [Git Tags](#git-tags)
- [Git Behind The Scenes](#git-behind-the-scenes)
- [Reflogs](#reflogs)
- [Custom Aliases](#custom-aliases)

## Installation

- [Git for Windows](https://git-scm.com/download/win)
- [Git for Mac](https://git-scm.com/download/mac)
- [Binary installer for Mac](https://sourceforge.net/projects/git-osx-installer/)
- [VS Code Installation](https://code.visualstudio.com/download)
- [GitKraken](https://www.gitkraken.com/)

## Git Commands

### Check your Git version

```bash
git --version
```

### Configuring Git

```bash
git config --global user.name "[firstname lastname]"
git config --global user.email "[valid-email]"
```

### Git Status

```bash
git status
```

### Initializing a Git Repository

```bash
git init
```

```bash
git init -b main
```

### Staging Changes

```bash
git add .
```

### Committing Changes

```bash
git commit
```

```bash
git commit -m "your message"
```

### Remote Repository

```bash
git remote add origin <url>
```

```bash
git push -u -f origin main
```

### List Files and Directories

```bash
ls
```

```bash
ls -a
```

### Branching

```bash
git branch
```

```bash
git branch <branch-name>
```

```bash
git switch <branch-name>
# or
git checkout <branch-name>
```

```bash
git switch -c <branch-name>
# or
git checkout -b <branch-name>
```

### Fetching and Pulling

```bash
git branch -a
```

```bash
git fetch origin <branch-name>
```

```bash
git pull origin <branch-name>
```

### Merging

```bash
git merge <branch-name>
```

### Deleting Branches

```bash
git branch -d <branch-name>
```

```bash
git branch -D <branch-name>
```

### Renaming a Branch

```bash
git branch -m <new-branch-name>
```

### Amending Commits

```bash
git commit --amend
```

### Git Tags

```bash
git tag -a <tag-name> -m "tag message"
```

### Git Behind The Scenes

```bash
git cat-file -t <hash>
git cat-file -p <hash>
```

### Reflogs

```bash
git reflog <branch-name>
```

### Custom Aliases

```bash
git config --global alias.<alias-name> "<git-command>"
```

## Exercise

- [Committing Basics Exercise](https://plum-poppy-0ea.notion.site/Committing-Basics-Exercise-3dc1ef1873ce45e68cedd2265710d7d8/): A basic assignment on Committing Basics.
- [Branching Exercise](https://plum-poppy-0ea.notion.site/Branching-Exercise-b5460c881d56400cb046357d9a430bf8): An assignment on Branching.

## Authors

- [@AhmadPiracha](https://www.github.com/AhmadPiracha)

## Support

For support, email ahmadpiracha3@gmail.com
