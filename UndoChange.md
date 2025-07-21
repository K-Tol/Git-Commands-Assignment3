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

## git checkout file
```bash
git checkout -- <file>
```

### What it does:
This gets rid of any changes to that file and restores it to the previous commit's version

### Narrative:
Great if you want to discard any un-needed changes or made change by accident, and want to go back
to a previous commit.

## git restore file
```bash
git restore <file>
```

### What it does:
A modern way of restore a file to the last commited version

### Narrative:
A more modern version of checkout file, leading to less errors due to checkout having multiple functions.
Restore is only for file restoration.