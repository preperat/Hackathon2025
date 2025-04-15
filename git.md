# GitHub Quick Reference

## Initial Global Setup (One-time)
```bash
# Set global git config
git config --global user.name "preperat"
git config --global user.email "your.email@example.com"

# Set GitHub CLI config
gh config set editor "code --wait"
gh config set git_protocol ssh
```

## New Project Setup
```bash
# Create new repo
gh repo create <repo-name>

# Initialize and connect
git init
git remote add origin git@github.com:preperat/<repo-name>.git
```

## Common Commands
```bash
# Add and commit
git add .
git commit -m "message"

# Push changes
git push

# Pull changes
git pull

# Check status
git status
```

## Authentication Methods
### Primary: Passkey (Recommended)
- Using 1Password passkey "1passwdGitHub"
- Created Apr 15, 2025
- Most secure option
- Works across devices with 1Password

### Backup: SSH/PAT
- SSH Key: ~/.ssh/id_ed25519
- PAT stored in system keychain
- No need to re-authenticate unless:
  - PAT revoked
  - SSH keys changed
  - Using different computer 