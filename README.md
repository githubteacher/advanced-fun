# Welcome to "Advanced" Git



- **Date:** January 23, 2017 
- **Facilitators:** @crichID and @hectorsector
- **Class Chat:** [![Join the chat at https://gitter.im/advanced-fun/Lobby](https://badges.gitter.im/advanced-fun/Lobby.svg)](https://gitter.im/advanced-fun/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Session Outline

- Understanding how commits are made
- Initializing a local Git repository
  - What is happening "under the hood" when we issue core git commands
  - git log
  - git diff
- Working with branches
  - Merge strategies
  - Understanding rebase
- Get out of anything (understanding the git "undo" commands)
  - Git revert
  - Git commit amend
  - Git reset
  - Git reflog
  - Git cherry-pick
  - Git filter-branch
- Other git features
  - Git bisect
  - Git stash
- Q&A
  - Git GUIs

## Scripts for Adding Files

- **Bash:** `for d in {1..6}; do touch file$d.md; git add file$d.md; git commit -m "adding file $d"; done`
- **PowerShell:** `for ($d=1; $d -le 6;$d++) { touch file$d.md; git add file$d.md; git commit -m "adding file$d.md";}`

## A Few Resources

- [git-scm](https://git-scm.com)
- [LearnGitBranching](http://learngitbranching.js.org/?NODEMO)
- [GitSchool - Visualizing Git](http://git-school.github.io/visualizing-git/)

