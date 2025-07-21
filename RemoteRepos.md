## git remote -v
```bash
git remote -v
```

### What it does:
Shows you which repos are linked to your local git repo

### Narrative:
This is great to see which remote repo your local repo is connected to, if you have a lot of repos.
Also great for troubleshooting fetch, pull, or push issues.

## git push
```bash
git push <remote> <branch>
```

### What it does:
This is used to send any changes from a local repo to a remote one

### Narrative:
Typically remote is set to origin. Once used, depending on the branch sent to, said push will either result in a
direct change if sent to main/master, or be sent to be reviewed as a pull request.

## git pull
```bash
git pull <remote> <branch>
```

### What it does:
This takes changes from the remote repo and brings it to the local repo

### Narrative:
Helps with keepeing your local repo up to date, especailly when working with others.
If your local branch is alreadying tracking a remote one, you can shorten the command to just git pull.
