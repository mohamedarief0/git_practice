## Changing Git Commit Author Information
## personal to office
### Case 1: Accidentally Committed from Personal Account, Want to Switch to Office Account

If you mistakenly committed with your personal GitHub account and need to change the commit author to your office account:

```bash
# Check the commit made with personal account
git log --oneline --author="arief@gmail.com"

# Amend the commit with office account details
git commit --amend --author="mohamedarief-office <mohamedarief@office.io>"

# Force push the changes to the remote repository
git push origin main --force

```

## Office to personal
### Case 2: Accidentally Committed from Office Account, Want to Switch to Personal Account

If you mistakenly committed with your office GitHub account and want to change the commit author to your personal account:

```bash
# Check the commit made with office account
git log --oneline --author="mohamedarief@office.io"

# Amend the commit with personal account details
git commit --amend --author="mohamedarief01 <arief@gmail.com>"

# Force push the changes to the remote repository
git push origin main --force

```
