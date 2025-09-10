## Keeping Your Fork Updated
This repo gets frequent updates. To make sure your fork stays in sync:

### Option 1: GitHub UI (easy way)
1. Go to your fork on GitHub.
2. Click the **Sync fork** button (top right).
3. Click **Update branch**.

### Option 2: Git CLI (advanced way)
If you cloned your fork locally:
```bash
git remote add upstream https://github.com/YOUR-USERNAME/YOUR-REPO.git
git fetch upstream
git checkout main
git merge upstream/main   # or git rebase upstream/main
git push origin main
