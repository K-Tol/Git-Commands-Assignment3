## git reset soft
```bash
git reset --soft HEAD-1
```

### What it does:
This moves the HEAD pointer to a specific commit, but keeps both working directory and stageing area untouched

### Narrative:
This is great if you wanted to adjust the last commit sent.

## git reset mixed
```bash
git reset --mixed HEAD-1
```

### What it does:
This moves the HEAD pointer to a specific commit, keeps both working directory , but unstages all changes

### Narrative:
The default for reset if you don't specify which version you want. Great for re-editing/regrouping changes
before doing another commit.

## git reset hard
```bash
git reset --hard HEAD-1
```

### What it does:
This moves the HEAD pointer to a specific commit, and resets both working directory and staging area

### Narrative:
This is used when you want a clean slate and have no care for any uncommited changes til then. Must be used
sparingly due to how destructive it is.