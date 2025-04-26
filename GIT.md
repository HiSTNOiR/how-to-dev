# HOW TO GIT

| HOW TO ...                                                                                       | DATE ADDED |
| ------------------------------------------------------------------------------------------------ | ---------- |
| [create a new git repo (using gh in the CLI)](#how-to-create-a-new-git-repo-using-gh-in-the-cli) | 2025 04 27 |

---

## How to create a new git repo (using gh in the CLI)

In the project's directory (and you're logged in/auth'd):

1. `git init`
2. Make `.gitignore` file
3. `git add .`
4. `git commit -m 'message'`
5. `gh repo create REPO_NAME --private -s . --push`
   - `-s` uses the current directory and pushes its commits
