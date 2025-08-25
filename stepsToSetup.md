## 1 — Install Tools
Install Git (git-scm.com)
Install VSCode (code.visualstudio.com)
Make a GitHub account

## 2 — Prepare GitHub
On GitHub click New Repository
Name it → Create repository
Copy the HTTPS URL (ends in .git)

## 3 — Open VSCode
File → Open Folder → pick your project folder
View → Terminal in VSCode

## 4 — Connect Folder to Repo
In terminal (first time only):
git init
git remote add origin <paste-URL>

## 5 — First Commit & Push
git add .
git commit -m "first commit"
git branch -M main
git push -u origin main

## 6 — Ongoing Workflow

Edit files
VSCode → Source Control (branch icon)
Stage (+) → Commit (message) → Push (↑)

## 7 — Pull Updates (for collaborating)

If repo has new changes, in VSCode terminal, enter: 
git pull

