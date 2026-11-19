# Git and GitHub — Beginner Cheat Sheet

## What the words mean
- Repository: project folder tracked by Git.
- Git: version history tool on your computer.
- GitHub: website hosting your repository.
- Commit: named snapshot saved locally.
- Push: upload commits to GitHub.
- Pull: download commits from GitHub.
- `git status`: see what changed.

## One-time setup (run once)
```powershell
git config --global user.name "Your Name"
git config --global user.email "your-github-email@example.com"
```

Use your GitHub email or GitHub-provided noreply address. Do not publish personal data unnecessarily.

## Daily workflow
Run these from inside your repository:
```powershell
git status
git add .
git commit -m "Describe what changed"
git push
```

## If Git says nothing to commit
It means Git sees no new changes. Check that you saved your file and are in the correct folder:
```powershell
Get-Location
git status
```

## If Git says author identity unknown
Run the one-time setup above, then retry commit.

## If push asks you to authenticate
Complete GitHub's browser sign-in. Never paste a password or personal access token into a chat.

## Safety
Never commit `.env`, passwords, API keys, tokens, private keys, or real customer data. Add secrets to `.gitignore`.
