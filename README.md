# Git & GitHub Cheat Sheet🚀
Here's the entire Git & GitHub Cheat Sheet in one place for easy copying:
## Git Basics


### Configure Git
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
### Create a Repository
```
git init
```
### Clone a Repository
```
git clone <repository-url>
```
### Add Changes
```
git add <filename>
git add .
```
### Commit Changes
```
git commit -m "Your commit message"
```

### Check Status
```
git status
```

### View Commit History
```
git log
```

### Create a Branch
```
git branch <branch-name>
git checkout -b <branch-name>
```
### Switch Branches
```
git checkout <branch-name>
```
### Merge Branches
```
git merge <branch-name>
```
## Resolve Conflicts
Manually resolve conflicts in files.
```
git add <filename>
```
```
git commit -m "Merge conflict resolution"
```
### Undo Changes
```
git reset HEAD <filename>
git checkout -- <filename>
```

### Remote Repositories
```
git remote add origin <repository-url>
git remote -v
```

### Push Changes
```
git push -u origin <branch-name>
```

### Pull Changes
```
git pull origin <branch-name>
```

### Tagging
```
git tag -a v1.0 -m "Version 1.0"
git push origin --tags
```
# GitHub
## Create a Repository
Click on the '+' sign in the top right corner.
Select 'New Repository.'
## Fork a Repository
Click 'Fork' on GitHub.
## Clone a Repository
```
git clone <forked-repository-url>
```
## Pull Requests
Create a new branch.
Make changes, commit, and push.
Go to the original repository on GitHub.
Click 'New Pull Request.'
## Issues
Go to the 'Issues' tab on GitHub.
Click 'New Issue.'
## GitHub Pages
Go to 'Settings.'
Scroll down to 'GitHub Pages' section.
Choose a branch for GitHub Pages.
## Collaborators
Go to 'Settings.'
Click 'Collaborators & teams.'
Add collaborators by username.
## Actions (CI/CD)
Create a .github/workflows/workflow.yml file.
Define workflow steps.
## GitHub CLI (gh)
```
gh repo create
gh issue create -t "New Issue" -b "Issue description"
gh pr create --base main --head feature-branch --title "Pull Request"

```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Regards : Engr Umair
## Follow Me On Facebook
More cheat sheets on the way!

[Facebook](https://www.facebook.com/umair.choudhary.9494/)
