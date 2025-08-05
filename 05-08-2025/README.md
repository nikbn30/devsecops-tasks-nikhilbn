# devsecops-tasks-nikhilbn
This repository contains DevSecOps Git-Hands on tasks

# DevSecOps Git Practice - <Your Name>
## Date: YYYY-MM-DD

### 🔧 Git Configuration
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
git config --list

### 📁 Repository Setup

git clone https://github.com/<your-username>/devsecops-tasks-<your-name>.git
cd devsecops-tasks-<your-name>
mkdir YYYY-MM-DD
cd YYYY-MM-DD
touch task1.txt task2.txt

### 📦 Staging and Committing

git status
git add .
git commit -m "Initial commit with two task files"

### 🔁 Making Changes

echo "This is Task 1 content" >> task1.txt
git status
git add task1.txt
git commit -m "Updated task1.txt with content"

### 🧾 Logs and Show

git log
git show <commit-id>

### 🚀 Push to GitHub
git push origin main

### 🔁 Pull Remote Changes
git pull

