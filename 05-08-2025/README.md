# devsecops-tasks-nikhilbn
This repository contains DevSecOps Git-Hands on tasks

# DevSecOps Git Practice - <Your nikhil.bn>
## Date: 2025-08-05

### 🔧 Git Configuration
git config --global user.name "nikhil.bn"
git config --global user.email "nikhil.bn30@gmail.com"
git config --list

### 📁 Repository Setup

git clone https://github.com/<nikhil.bn>/devsecops-tasks-<nikhil.bn>.git
cd devsecops-tasks-<nikhil.bn>
mkdir 2025-08-05
cd 2025-08-05
touch task1.txt task2.txt

### 📦 Staging and Committing

git status
git add task1.txt task2.txt.
git commit -m "Initial commit with two task files"

### 🔁 Making Changes

echo "This is Task 1 content" >> task1.txt
git status
git add task1.txt
git commit -m "Updated task1.txt with content"

### 🧾 Logs and Show

git log
git show <60e0e22>

### 🚀 Push to GitHub
git push origin main

### 🔁 Pull Remote Changes
git pull

