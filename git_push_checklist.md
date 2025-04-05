# Git Push Checklist (Mobile-Friendly via Termux)

## Step-by-step to push from Termux on Android

```bash
# 1. Navigate to your working folder (adjust if your path is different)
cd ~/storage/shared/Documents/mythtech-archive

# 2. Initialize Git (only once per repo)
git init

# 3. Add all files for commit
git add .

# 4. Commit with message
git commit -m "Pushing updated game modules and scripts"

# 5. Link your GitHub repo (only once)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git branch -M main

# 6. First time push
git push -u origin main

# 6b. Future updates
git push
```

## Useful Extras

```bash
# Check file status
git status

# Check remote URL
git remote -v

# Change commit message if needed
git commit --amend
```

Save this in your root lore directory as `git_push_checklist.md` for quick reuse.
