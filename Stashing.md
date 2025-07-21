## git stash
```bash
git stash
```

### What it does:
Allows you to temporarily save your uncommited work, allowing you to do other stuff

### Narrative:
Uncommited work encompasses both tracked and untracked work. You can even switch branches
or pull changes before commiting any work

## git stash
```bash
git stash pop
```

### What it does:
Reapplies the last stashed changes and removes them from the stash list

### Narrative:
Be mindful to your stash changes compared to your current directory, conflicts will arise if
you're not careful. Also when you have multiple stashes, add the stash@{#} after pop where
'#' is the numbered stash you want.