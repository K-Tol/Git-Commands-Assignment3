## git stash
```bash
git stash
```

### What it does:
Allows you to temporarily save your uncommited work, allowing you to do other stuff

### Narrative:
Uncommited work encompasses both tracked and untracked work. You can even switch branches
or pull changes before commiting any work

## git stash pop
```bash
git stash pop
```

### What it does:
Reapplies the last stashed changes and removes them from the stash list

### Narrative:
Be mindful to your stash changes compared to your current directory, conflicts will arise if
you're not careful. Also when you have multiple stashes, add the stash@{#} after pop where
'#' is the numbered stash you want.

## git stash apply
```bash
git stash apply
```

### What it does:
Reapplies the last stash, but keeps a copy of the stash in the stash list

### Narrative:
This version of stash is great if you want to reapply a stash over and over again. Same rules
apply from other stash commands when it comes to specific stashes you want applied.

## git stash save "message"
```bash
git stash save "message"
```

### What it does:
Save current changes to the stash list with a message of your choice

### Narrative:
Workes the same as the regeular stash command but is an older way of saving with a message.
Said messages can be helpful for identification when browsing the list.