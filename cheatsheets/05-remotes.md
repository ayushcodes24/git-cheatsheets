## check connected remote repositories

### shows the fetch and push URLs for your remote repositories

```bash
git remote -v
```

## rename current branch to main

```bash
git branch -M main (renames current local branch to 'main')
```

## add github remote repository

### link local to remote repository

```bash
git remote add origin <remote-repository-link>
```

## pushing code to remote repository with adding an upstream

### push local 'main' to remote 'origin' & set upstream

```bash
git push -u origin main
```

### after setting an upstream, future pushes from this branch can be done with this simpler command

```bash
git push
```

## clone a github repository

### download existing repository to local

```bash
git clone <repository-link>
```

## pull changes from remote

### fetch & merge latest remote changes

```bash
git pull
```

### fetch & merge 'main' from 'origin'

```bash
git pull origin main
```

## fetch changes from remote

### download latest remote changes (without merging)

```bash
git fetch
```

## change remote URL

### update existing remote repository URL

```bash
git remote set-url origin <new-repo-link>
```

## remove remote

### disconnect local from remote repository

```bash
git remote remove origin
```
