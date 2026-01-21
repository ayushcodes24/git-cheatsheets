## checking git version

```bash
git --version
```

## global configuration (One-Time Setup)

### set email

```bash
git config --global user.email "email@example.com"
```

### set username

```bash
git config --global user.name "name"
```

### set default code editor

```bash
git config --global core.editor "code --wait"
```

### line ending configuration (Important for Cross Platform projects)

```bash
git config --global core.autocrlf "input"
```

## view and edit git configuration

### open global config file in editor

```bash
git config --global -e
```

### list all global configurations

```bash
git config --global --list
```

## creating a repository

### initialize a new git repository

```bash
git init
```

### check repository status (detailed)

```bash
git status
```

### short status

```bash
git status -s
```
