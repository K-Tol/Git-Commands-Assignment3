## git status
```bash
git status
```
### What it does:
This shows the state of the working directory

### Narrative:
All the changes in regards to staging and tracking are shown with this command. Staged and unstaged may even show
in a different color depending on the ide used.

## git add
```bash
git add <file>
```
### What it does:
Takes a change made with a file and moves it onto the staging phase

### Narrative:
Affectivly a pre-planning step, where a file update is almost ready to be commited. Since it is only a pre-commit step
until the commit command is ran, the change is not fully recorded yet to the repository.

## git add .
```bash
git add .
```

### What it does:
Similar with add file, but it takes the whole current directory and stages it

### Narrative:
This version of add takes all files, folders, and others and stages it. There are other add files commands but this one
allows you to stage files that start with a period.

## git commit -m
```bash
git commit -m "Your message"
```

### What it does:
This commits a change with an message attached to it

### Narrative:
This is the next step in the update process, right after staging. This finialize a change and records it in the remote
repository. A message is attached to show some  info about the commit.

## git commit -am
```bash
git commit -am "Your message"
```

### What it does:
Shorthand command that stages tracked files and commits with a message

### Narrative:
Very similar to the -m version, this one tacks on the addition of staging files. Said files must have been tracked already in
order to work, other wise a git add command must occur first.