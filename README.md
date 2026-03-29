 Assignment: Upload Project to GitHub using Git

## Procedure:

### 1) Create a new repository on GitHub.com
To avoid errors, do not initialize the new repository with README, license, or .gitignore files. You can add these files after your project has been pushed to GitHub.

---

### 2) Open Terminal (Git Bash / PowerShell)

---

### 3) Change the current working directory to your local project

```bash
cd C:\Users\Sanika\OneDrive\Desktop\wad\ass1b
4) Initialize the local directory as a Git repository
git init -b main
5) Add the files in your local repository
git add .

Adds the files in the local repository and stages them for commit.
To unstage a file, use git reset HEAD YOUR-FILE.

6) Commit the files
git commit -m "First commit"

Commits the tracked changes and prepares them to be pushed to a remote repository.

7) Copy the remote repository URL
https://github.com/SanikaDeokar09/assginment-2b.git
8) Add the remote repository
git remote add origin https://github.com/SanikaDeokar09/assginment-2b.git
git remote -v

Sets and verifies the remote repository URL.

9) Push the changes to GitHub
git push -u origin main

Pushes the changes in your local repository to GitHub.
