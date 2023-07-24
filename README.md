# git-commands

This repository contains useful git commands for our git flow.

## Setup

1. On your Mac, open a terminal then :

```
cd /Users/<your username>/
git clone git@github.com:ithaque-renovation/git-commands.git
```

2. Then edit the file `~/.zshrc` (if you are using ZSH) or `~/.bashrc` (if you are using bash). Add the line :

```
export PATH="$PATH:$HOME/git-commands"
```

3. Open a new terminal, you now have access to new git-commands.

## Commands

You can now use these commands in any git repository.

### git cleanup

Deletes branches that have been merged into `dev` branch.

### git fixup

Opens interactive list of commits in the current repo. You can pick a chosen commit, this will create a fixup commit from the current staged changes.

### git pr

Enter a Title and an optionnal Description. This will push the current branch and create 1 pull request on `dev` and 1 pull request on `main`.
