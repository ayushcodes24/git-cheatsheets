# Git and GitHub Commands Reference

This repository serves as a quick and easy reference for commonly used Git and GitHub commands. The commands are organized into granular files within the `cheatsheets/` directory for easier navigation:

- [**`01-setup.md`**](cheatsheets/01-setup.md): Git installation, initial configuration, and repository management.
- [**`02-workflow.md`**](cheatsheets/02-workflow.md): Staging, committing, and temporarily saving unfinished work (stashing).
- [**`03-history-and-diff.md`**](cheatsheets/03-history-and-diff.md): Viewing commit history and comparing changes between various states.
- [**`04-branching.md`**](cheatsheets/04-branching.md): Creating, switching, merging, and deleting branches.
- [**`05-remotes.md`**](cheatsheets/05-remotes.md): Managing remote repositories (GitHub-related commands).
- [**`06-undoing.md`**](cheatsheets/06-undoing.md): Undoing commits, discarding changes, and safely rewriting history (revert/rebase).

## How to Use

Simply click on any of the links above or navigate to the `cheatsheets/` directory and open the relevant `.md` file. Each command is accompanied by a short, descriptive explanation.

## Essential Daily-Use Git Commands

Based on common developer workflows, here are the top 15 commands you'll likely use every day:

| Command                   | Purpose                                                             |
| :------------------------ | :------------------------------------------------------------------ |
| `git status`              | Check the state of your working directory and staging area.         |
| `git add .`               | Stage all current changes for the next commit.                      |
| `git commit -m "msg"`     | Save your staged changes with a descriptive message.                |
| `git pull`                | Fetch from and integrate with another repository or a local branch. |
| `git push`                | Update remote refs along with associated objects.                   |
| `git switch -c <name>`    | Create a new branch and switch to it immediately.                   |
| `git switch <name>`       | Switch to an existing branch.                                       |
| `git merge <name>`        | Join two or more development histories together.                    |
| `git log --oneline`       | View a condensed version of the project history.                    |
| `git clone <url>`         | Clone a repository into a new directory.                            |
| `git stash`               | Stash the changes in a dirty working directory away.                |
| `git diff`                | Show changes between commits, commit and working tree, etc.         |
| `git branch`              | List, create, or delete branches.                                   |
| `git fetch`               | Download objects and refs from another repository.                  |
| `git reset --soft HEAD~1` | Undo the last commit while keeping your changes staged.             |

## Contributions

Feel free to suggest improvements or additional commands by opening an issue or a pull request!
