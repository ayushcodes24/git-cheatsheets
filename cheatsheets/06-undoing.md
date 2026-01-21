## undo/revert changes

### remove last commit, keep changes staged

```bash
git reset --soft HEAD~1
```

### remove last commit, keep changes unstaged

```bash
git reset --mixed HEAD~1
```

### remove last commit, discard all changes (DANGEROUS)

```bash
git reset --hard HEAD~1
```

## discarding every changes after commit

### discard changes in working directory for a file

```bash
git restore <file-name>
```

### unstage changes for a file, keep in working directory

```bash
git restore --staged <file-name>
```

### discard changes in working directory for a folder

```bash
git restore <folder-name>
```

### unstage changes for a folder, keep in working directory

```bash
git restore --staged <folder-name>
```

### discard all changes in working directory

```bash
git restore .
```

### unstage all changes, keep in working directory

```bash
git restore --staged .
```

## undoing commits safely (Reverting)

### create new commit to undo specific commit (safer undo)

```bash
git revert <commit-id>
```

## cleaning up history (Rebasing)

### rewrite commit history (use with caution)

```bash
git rebase
```
