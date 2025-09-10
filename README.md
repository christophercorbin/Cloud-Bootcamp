# Cloud-Bootcamp
Help mee 

Git Configuration
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list                # View config

Repository Setup

git init                         # Initialize a new repo in current directory
git clone <url>                  # Clone an existing repo

Basic File Operations
git status                       # Show changes
git add <file>                   # Stage specific file
git add .                        # Stage all files
git reset <file>                 # Unstage file

git commit -m "message"          # Commit staged changes
git commit -am "message"         # Add & commit tracked files

Branching

git branch                       # List branches
git branch <name>                # Create a new branch
git checkout <name>              # Switch to branch
git checkout -b <name>           # Create + switch
git branch -d <name>             # Delete branch

Merging & Rebasing

git merge <branch>               # Merge into current branch
git rebase <branch>              # Reapply commits on top of branch
git log --oneline --graph --all  # Visualize branches


Remote Repositories
git remote -v # Show remotes
git remote add origin # Add remote
git push -u origin # Push branch
git pull origin # Pull branch
git fetch # Download latest refs

Undo / Fix Mistakes
git restore # Restore file
git reset --hard HEAD # Reset last commit
git reset --hard # Reset specific commit
git revert # Revert commit

Stashing
git stash # Save changes
git stash list # List stashes
git stash apply # Apply latest stash
git stash pop # Apply & drop stash

History & Logs
git log # Full history
git log --oneline # Compact history
git diff # Unstaged changes
git diff --staged # Staged changes


Tagging
git tag # List tags
git tag # Create tag
git push origin # Push tag
git push --tags # Push all tag
