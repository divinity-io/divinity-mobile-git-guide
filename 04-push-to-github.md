# 📱 04 - Push Project to GitHub from Mobile

## Introduction

In this chapter, we learn how to upload a project from Termux on a mobile phone to GitHub.

You can write code, manage files, and publish your projects without a PC.

---

# Create a Repository on GitHub

Before pushing code:

1. Login to GitHub.
2. Create a new repository.
3. Copy your repository URL.

Example:

```
https://github.com/username/project-name.git
```

---

# Open Your Project Folder

Move into your project directory:

```bash
cd my-project
```

---

# Initialize Git

If Git is not initialized:

```bash
git init
```

---

# Add Project Files

Add all files:

```bash
git add .
```

---

# Create a Commit

Save your changes:

```bash
git commit -m "First project upload"
```

---

# Connect GitHub Repository

Add your GitHub repository:

```bash
git remote add origin https://github.com/username/project-name.git
```

Replace:

```
username/project-name.git
```

with your own repository link.

---

# Rename Branch to Main

Set your branch name:

```bash
git branch -M main
```

---

# Push Code to GitHub

Upload your project:

```bash
git push -u origin main
```

Your code is now available on GitHub.

---

# Update Existing Projects

After making changes:

Check changes:

```bash
git status
```

Add changes:

```bash
git add .
```

Commit:

```bash
git commit -m "Updated project"
```

Push:

```bash
git push
```

---

# Clone a GitHub Project

Download an existing project:

```bash
git clone https://github.com/username/project-name.git
```

Enter the project:

```bash
cd project-name
```

---

# Useful Git Commands

Check remote repository:

```bash
git remote -v
```

View commits:

```bash
git log
```

Check current branch:

```bash
git branch
```

Clear terminal:

```bash
clear
```

---

# Congratulations 🎉

You have learned how to:

✅ Install development tools  
✅ Configure Git  
✅ Create projects on mobile  
✅ Push code to GitHub  

Your phone is now a mobile development workstation.

---

# Mission

Code First.  
Security Always.  
Impact Forever.

⚡ Divinity Mobile Git Guide
