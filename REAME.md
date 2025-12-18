📌 Git Basic Commands Cheat Sheet

This document contains commonly used Git commands for initializing a repository, managing branches, and connecting to GitHub.

🔹 Git Initialization
git init

🔹 Add Files to Staging Area
git add .

🔹 Commit Changes
git commit -m "Commit_message"

🔹 Rename / Connect to Main Branch
git branch -M main

🔹 Create a New Branch
git branch branch_name
git checkout branch_name

🔹 Switch Branch
git switch branch_name

🔹 Create and Switch Branch (Shortcut)
git switch -c branch_name

# OR

git checkout -b branch_name

🔹 Connect Local Repo to Remote Repository
git remote add origin <REMOTE_REPO_URL>

🔹 Push Code to Remote Repository
git push -u origin main

🔹 Set GitHub Username
git config --global user.name "Your_GitHub_Username"

# Local (only for this project)

git config --local user.name "Your_GitHub_Username"

🔹 Set GitHub Email
git config --global user.email "your_email@example.com"

# Local (only for this project)

git config --local user.email "your_email@example.com"

🔹 Check Git Configuration
git config --list

🔹 Check Repository Status
git status

🔹 Check Connected Remote Repository
git remote -v

🔹 Remove (Unset) GitHub Username
git config --global --unset user.name

🔹 Remove (Unset) GitHub Email
git config --global --unset user.email
