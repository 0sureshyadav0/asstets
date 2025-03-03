# Git Mastery: From Beginner to Pro

## Module 1: Introduction to Git

### What is Git?
Git is a **distributed version control system** that helps developers track changes in their code, collaborate with others, and maintain different versions of a project efficiently.

### Why Use Git?
- Allows multiple developers to work on a project simultaneously.
- Keeps track of all changes, making it easy to revert to previous versions.
- Enables branching and merging for better development workflow.
- Supports collaboration through remote repositories (GitHub, GitLab, Bitbucket).

### Git vs. GitHub, GitLab, Bitbucket
- **Git** is the actual version control system.
- **GitHub, GitLab, Bitbucket** are cloud-based platforms that host Git repositories and provide collaboration features.

### Installing Git
#### Windows
1. Download Git from [git-scm.com](https://git-scm.com/).
2. Install using default settings.
3. Verify installation:
   ```sh
   git --version
   ```

#### Linux (Debian/Ubuntu-based)
```sh
sudo apt update
sudo apt install git
```

#### macOS
```sh
brew install git
```

### Configuring Git
Set up your name and email:
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
Check settings:
```sh
git config --list
```

## Module 2: Git Basics

### Initializing a Repository (`git init`)
Start tracking a project:
```sh
git init
```

### Cloning a Repository (`git clone`)
Download a copy of a remote repository:
```sh
git clone <repository_url>
```

### Understanding the Git Workflow
1. **Working Directory** - Your project files.
2. **Staging Area** - Changes you want to commit.
3. **Repository** - Commits stored in Git history.

### Tracking Files
#### Add files to the staging area
```sh
git add <file>  # Add a specific file
git add .       # Add all files
```
#### Check status
```sh
git status
```

### Committing Changes (`git commit`)
Save changes permanently in Git history:
```sh
git commit -m "Your commit message"
```

### Viewing Commit History (`git log`)
```sh
git log --oneline
```

## Module 3: Working with Branches

### Creating a Branch (`git branch`)
```sh
git branch feature-branch
```

### Switching Branches (`git switch`)
```sh
git switch feature-branch
```

### Merging Branches (`git merge`)
```sh
git checkout main
git merge feature-branch
```

### Deleting Branches
```sh
git branch -d feature-branch
```

### Resolving Merge Conflicts
Manually edit conflicting files and mark them as resolved:
```sh
git add conflicted-file
git commit -m "Resolved merge conflict"
```

## Module 4: Remote Repositories

### Connecting to a Remote Repository (`git remote add`)
```sh
git remote add origin <repository_url>
```

### Pushing Changes (`git push`)
```sh
git push origin main
```

### Pulling Changes (`git pull`)
```sh
git pull origin main
```

### Fetching Updates (`git fetch`)
```sh
git fetch
```

## Module 5: Collaborative Workflows

### Forking and Cloning Repositories
- **Forking**: Copying someone else’s repository to your GitHub.
- **Cloning**: Downloading a repository locally.

### Working with Pull Requests
1. Fork a repository.
2. Clone it locally.
3. Make changes and push them.
4. Open a pull request on GitHub.

## Module 6: Undoing Changes and Fixing Mistakes

### Discarding Local Changes
```sh
git restore <file>
```

### Undoing Commits
```sh
git reset --soft HEAD~1  # Keep changes
git reset --hard HEAD~1  # Remove changes
```

### Reverting a Commit (`git revert`)
```sh
git revert <commit-hash>
```

### Stashing Changes (`git stash`)
```sh
git stash
git stash pop
```

## Module 7: Advanced Git Techniques

### Rewriting History with `git rebase`
```sh
git rebase main
```

### Cherry-picking Commits (`git cherry-pick`)
```sh
git cherry-pick <commit-hash>
```

### Using `git bisect` for Debugging
```sh
git bisect start
git bisect bad
git bisect good <commit-hash>
```

## Module 8: Git Hooks and Automation

### Pre-commit Hook Example
Create `.git/hooks/pre-commit`:
```sh
#!/bin/sh
echo "Running pre-commit hook..."
```
Make it executable:
```sh
chmod +x .git/hooks/pre-commit
```

## Module 9: Git Best Practices

### Writing Meaningful Commit Messages
Follow this format:
```
feat: Add new feature
fix: Fix bug in feature X
refactor: Improve code structure
```

### Using `.gitignore`
Ignore files like logs or temporary files:
```
node_modules/
.env
*.log
```

## Module 10: Git Tools and GUI Clients

### Using Git in VS Code
- Integrated Git panel for commits, branching, and merging.

### Visualizing Git History
```sh
git log --graph --all --decorate --oneline
```

## Final Project: Real-World Git Workflow
- Set up a project with feature branches.
- Implement pull requests and code reviews.
- Merge and deploy the project.

---
This Markdown file serves as a **complete guide to mastering Git**. 🚀
