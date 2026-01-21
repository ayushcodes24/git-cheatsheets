## view commit history

### full commit history

```bash
git log
```

### one-line commit summary

```bash
git log --oneline
```

### graph view (branches & commits)

```bash
git log --graph --oneline --all
```

## compare changes

### show changes: working directory vs last commit

```bash
git diff
```

### show changes: staged vs last commit

```bash
git diff --staged
```

### show changes: two specific commits

```bash
git diff <recent-commit-id> <older-commit-id>
```
