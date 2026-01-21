## branching

### create a new branch with the specified name

```bash
git branch branch-name
```

### list all local branches

```bash
git branch
```

### display current active branch name

```bash
git branch --show-current
```

### switch to an existing branch (older method)

```bash
git checkout branch-name
```

### create & switch to a new branch (older method)

```bash
git checkout -b branch-name
```

### go back to a specific commit (detached HEAD)

```bash
git checkout <commit-id>
```

### switch to an existing branch (recommended for clarity)

```bash
git switch branch-name
```

### create a new branch and switch to it immediately (recommended)

```bash
git switch -c branch-name
```

### rename current branch

```bash
git branch -m new-name
```

### rename another branch

```bash
git branch -m old-name new-name
```

### merge specified branch into current

```bash
git merge branch-name
```

### delete merged local branch (safe)

```bash
git branch -d branch-name
```

### force delete local branch (DANGEROUS)

```bash
git branch -D branch-name
```
