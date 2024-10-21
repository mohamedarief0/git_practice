### Committing Small Changes
## 1. Committing Small Changes to the Same Last Commit
```bash
# Stage the additional changes
git add <file.name>

# Amend the last commit without changing the commit message
git commit --amend --no-edit

# Force push the changes to the remote repository (if needed)
git push -f

```

## 2. Amending the Last Commit and Updating the Commit Message
```bash
# Stage the additional changes
git add <file.name>

# Amend the commit with a new message
git commit --amend -m "Updating the commit message"

# Force push the amended commit to the remote repository
git push -f

```

## 3. Amending the Last Commit Without Changing Any Files
```bash
# Amend the last commit with a new message (without staging any files)
git commit --amend -m "New commit message without changing files"

# Force push the amended commit to the remote repository
git push -f
```

## 4. Changing the Author of the Last Commit
```bash
# Amend the last commit with a new author
git commit --amend --author="New Name <new-email@example.com>"

# Force push the amended commit to the remote repository
git push -f

```
