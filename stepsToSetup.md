## 1 — Tools You'll Need
* Git (git-scm.com) //// if this is not installed on lab computers we may have to start out a different way
* VSCode (code.visualstudio.com)
* A GitHub account

## 2 — Prepare GitHub
* On GitHub click `New Repository`
* Name it and click `Create repository`
* Copy the HTTPS URL (ends in .git)

## 3 — Open VSCode
* File → Open Folder → pick or create your project folder
* View → Terminal

## 4 — Connect Folder to Repo
* In terminal (first time only) ENTER:
    * git init
    * git remote add origin <paste-URL>

## 5 — First Commit & Push ENTER:
* git add .
* git commit -m "first commit"
* git branch -M main
* git push -u origin main

## 6 — Ongoing Workflow
Edit files in VSCode
VSCode → Source Control (branching icon)
* Stage (click the + sign be all files you want to stage) 
* Type a message about the commit 
* Click `Commit` → Push (↑)

## 7 — Pull Updates (for collaborating)

If repo has new changes, in VSCode terminal, enter: 
git pull

