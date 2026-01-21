## staging area

### stage specific files

```bash
git add <file1> <file2>
```

### stage every single change across the entire project

```bash
git add --all
git add -A (alias for git add --all)
```

### stage the changes within the current directory you're in

```bash
git add .
```

### stages all visible changes except for the deleted files

```bash
git add *
```

### delete any file and stage it both at once

```bash
git rm <file1>
```

### to force delete any file

```bash
git rm -f <file1>
```

### to remove file from the staging area, keep in working directory

```bash
git rm --cached <file1>
```

## commit changes

### commit staged files with message

```bash
git commit -m "commit message"
```

### stage all tracked files and commit them

```bash
git commit -am "commit message"
```

## saving unfinished work (Stashing)

### temporarily save modified/staged changes

```bash
git stash
```

### list all stashed changes

```bash
git stash list
```

### remove a stash entry

```bash
git stash drop
```

### apply and remove most recent stash

```bash
git stash pop
```

### apply most recent stash, keep in list

```bash
git stash apply
```

### apply and remove a specific stash entry

```bash
git stash pop stash@{0}
```

## gitignore

```bash
.gitignore (tells Git which files/folders to ignore)
```
