# 1. Starting a Git Repository

```bash
# one-time setup
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

# new project
mkdir my-project && cd my-project
git init                 # repository shuru
echo "# My Project" > README.md
git status               # kya change hua?
git add README.md        # staging area me daalo (ya: git add .)
git commit -m "Initial commit"
git log --oneline        # history dekho
```

## Key ideas
- **Working directory** -> **Staging area** (`git add`) -> **Repository** (`git commit`)
- `git status` hamesha check karte rahein.
- Commit message chhota aur clear likhein.
