# Git Cheatsheet

## Common Git Commands

### 1. Configure Git
- Set user name: `git config --global user.name "Your Name"`
- Set user email: `git config --global user.email "you@example.com"`

### 2. Create a New Repository
- `git init`

### 3. Clone a Repository
- `git clone <repository-url>`

### 4. Check Status
- `git status`

### 5. Add Changes
- Add all changes: `git add .`
- Add specific file: `git add <file-name>`

### 6. Commit Changes
- `git commit -m "Commit message"`

### 7. Push Changes
- `git push origin <branch-name>`

### 8. Pull Changes
- `git pull origin <branch-name>`

### 9. View Commit History
- `git log`

### 10. Create a Branch
- `git branch <branch-name>`

### 11. Switch Branches
- `git checkout <branch-name>`

### 12. Merge Branches
- `git merge <branch-name>`

### 13. Resolve Conflicts
- Open conflicting files and resolve conflicts manually.
- After resolving, add changes and commit.

### 14. Delete a Branch
- `git branch -d <branch-name>`

### 15. Tagging
- Create a tag: `git tag <tag-name>`
- Push tags: `git push origin --tags`
