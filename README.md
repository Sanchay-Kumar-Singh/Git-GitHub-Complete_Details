<h1># 🚀 Git & GitHub Complete Guide</h1>

---

## 📌 Overview

### 🔹 What is Git?
Git is a **distributed version control system** that tracks changes in source code and helps multiple developers collaborate efficiently on a project.

### 🔹 What is GitHub?
GitHub is a **cloud-based hosting platform** for Git repositories. It allows developers to store, manage, share, and collaborate on code online.

---

## 📂 1️⃣ Upload Files Using Drag & Drop

You can directly upload files to GitHub by:
- Opening your repository
- Clicking **Add file → Upload files**
- Dragging and dropping files
- Committing the changes

✅ Best for beginners and small updates.

---

## 💻 2️⃣ Clone Repository & Push Changes

```bash
git clone <repository_url>
git status
After adding a new file like README.txt:

git add .
git commit -m "Added README file"
git push origin main
🆕 3️⃣ Push Project Directly From Local Folder
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/username/repository-name.git
git push -u origin main
📌 This method is useful when starting a new project from scratch.

🌿 4️⃣ Working with Branches (Team Collaboration)
Different developers can work on different branches and later merge into the main branch.

🔹 Create Branches
git checkout -b feature1
git checkout -b feature2
git branch
🔹 Work on Feature Branch
git checkout feature1
git add .
git commit -m "Added feature 1"
git push origin feature1
git checkout feature2
git add .
git commit -m "Added feature 2"
git push origin feature2
🔹 Compare & Merge
git checkout feature1
git diff main
git checkout main
git merge feature2
git push origin main
🔹 Delete Branch
git branch -d feature2
🔁 4️⃣ (B) Compare & Merge on GitHub
Create a Pull Request on GitHub

Review changes

Merge into main

Pull updates locally:

git pull origin main
🔄 Undo Last Commit
git reset HEAD~1
📜 View Logs
git log
git reset <commit_code>
git reset --hard <commit_code>
🍴 5️⃣ Git Fork
A Git fork is a personal copy of someone else’s repository under your own GitHub account.

✅ Commonly used in open-source contributions.

🧑‍💻 6️⃣ Push & Create Repository from VS Code
Open project in VS Code

Run:

npm run build
Go to Source Control

Initialize repository

Commit & Push

GitHub repo will be created automatically

🌍 7️⃣ Deploy Project on GitHub Pages
Steps:

Go to Repository Settings

Click Pages

Select:

Branch: main

Folder: /root or /docs

Click Save

🚀 Your project is now live on GitHub Pages!

⭐ Key Benefits of Git & GitHub
Version control

Team collaboration

Backup & recovery

Open-source contributions

Easy deployment

🙌 Author
Sanchay Kumar Singh
💻 Computer Science & Engineering
