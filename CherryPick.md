## git cherry-pick <commit-hash>
```bash
git cherry-pick <commit-hash>
```

### What it does:
Takes one or multiple commits from a different branch and applies it to another

### Narrative:
Like the name entails, you grab a specific commit from on branch to another. This is great
if you want a specific change so that you don't have to merge entire branches. Be wary of
conflicts that may arise since you're bringing one change to another.