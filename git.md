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
### Web Browser Access
- Primary: 1Password Passkey "1passwdGitHub" (Created Apr 15, 2025)
  - Used for github.com web login only
  - Most secure option for website access
  - Works across devices with 1Password

### CLI and Git Operations
- SSH Key: ~/.ssh/id_ed25519 (for git push/pull)
- Personal Access Token (for GitHub CLI)
  - Stored in system keychain
  - Required for 'gh' command line operations
  - No need to re-authenticate unless:
    - Token is revoked
    - SSH keys changed
    - Using different computer 