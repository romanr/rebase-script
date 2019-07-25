# Git Rebase script
Script to rebase git branches on develop automatically. 
Simplifies the process of checking and updating branches during the rebase.

## 1. Makes it simple:
One command rather than typing at least 3-4 commands.

## 2. Safe:
It will not force push unless you confirm it.

## How it works:

Script will check out `develop` branch, pull and update `develop`. Then it will check out the specified branch and update it, then rebase and prompt you to force push the branch.  


### Usage:
To rebase current branch if you are not on `develop`:
```
rebase
```

Rebase specific branch:

```
rebase [branch name]
```
