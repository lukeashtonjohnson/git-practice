# Commands

## Tell git who you are

```
git config --global user.name "GitHub UserName"
git config --global user.email "Your Email address"
```

# Create a new local repository

```
git init
```

# Checkout a repository (Locally)

```
git clone /path/to/repository
```

# Checkout a repository (Remote User)

```
git clone username@host:/path/to/repository
```

# Add files

```
git add <filename>
git add *
git add .
```

# Commit your changes

```
git commit -m "commit message"
```

# Push files up to github

```
git push origin <branch name>
```

# Check the status of your work

```
git status
```

# Connect to a remote repository

```
git remote add origin <server>
```

# List all currently configured remote repositories

```
git remote -v
```

# Create new branch and switch to it

```
git checkout -b <branch name>
```

# switch from one branch to another branch

```
git checkout <branch name>
```

# List all branches

```
git branch
```

# Delete the featured branch (Locally)

```
git branch -D <local-branch>
```

# Delete the featured branch (Remotely)

```
git push origin --delete <remote-branch-name>
```

# Merge one branch into another branch

```
git merge <branch name>
```

# Stashing changes

```
git stash save "optional message for yourself"
```

# View Stashed changes

```
git stash list
```

# Applying Stashed changes and remove from stash

```
git stash pop
```

# Delete Stashed changes without applying them

```
git stash drop
```

# Clear the entire Stash

```
git stash clear
```
