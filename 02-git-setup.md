# 📱 02 - Git Setup on Mobile

## Introduction

In this chapter, we configure Git inside Termux.

Git allows developers to track changes, manage projects, and connect their code to GitHub.

---

# Check Git Installation

First, confirm Git is installed:

```bash
git --version
```

Example output:

```
git version 2.x.x
```

---

# Configure Git Username

Set your GitHub username:

```bash
git config --global user.name "YourUsername"
```

Replace:

```
YourUsername
```

with your actual GitHub username.

Example:

```bash
git config --global user.name "divinity-io"
```

---

# Configure Git Email

Use the email connected to your GitHub account:

```bash
git config --global user.email "your-email@example.com"
```

Example:

```bash
git config --global user.email "divinity@example.com"
```

---

# Check Git Configuration

View your Git settings:

```bash
git config --list
```

You should see:

```
user.name=YourUsername
user.email=your-email@example.com
```

---

# Set Main as Default Branch

Modern Git uses "main" as the default branch.

Run:

```bash
git config --global init.defaultBranch main
```

---

# Create Your First Git Project

Create a project folder:

```bash
mkdir my-first-project
```

Enter the folder:

```bash
cd my-first-project
```

Initialize Git:

```bash
git init
```

---

# Create Your First File

Create a README file:

```bash
nano README.md
```

Add your project information, then save.

---

# Check Git Status

Check your project:

```bash
git status
```

---

# Mission

Code First.  
Security Always.  
Impact Forever.

⚡ Divinity Mobile Git Guide
