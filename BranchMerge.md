## git branch
```bash
git branch
```

### What it does:
This allows you to see all the local branches

### Narrative:
When used you can see your current branch since it will have the '*' symbol next to it. This is also 
the basis for creating and deleting branches, which you need to add after the branch portion to do.

## git branch <branch-name>
```bash
git branch <branch-name>
```

### What it does:
This creates a new branch

### Narrative:
Coming from you current branch, you create a new branch. Keep it mind that this command only creates it,
you must mannually switch to said branch in order to work on it.

## git checkout <branch-name>
```bash
git checkout <branch-name>
```

### What it does:
Moves to the branch of your choice

### Narrative:
When used your working directory will match whatever branch you switch to.

## git switch <branch-name>
```bash
git switch <branch-name>
```

### What it does:
Newer way to move to the branch of your choice

### Narrative:
Does the same as git checkout in terms of dealing with branches, but was introduced to flow better
and to reduce confusion with checkout.

## git merge <branch-name>
```bash
git merge <branch-name>
```

### What it does:
Combines the changes from two branches

### Narrative:
It takes changes from a seperate branch and merges them in your current branch. You must be in the branch
you want to merge into before begining, like main/master for example.