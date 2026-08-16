# 📱 01 - Installing Termux

## Introduction

Welcome to Divinity Mobile Git Guide.

In this chapter, we prepare your phone for development using Termux.

No PC required.

Your phone can become a complete coding environment.

---

## What is Termux?

Termux is a terminal application for Android that allows you to run Linux commands, install development tools, write code, and manage projects.

---

## Requirements

Before starting:

- Android phone
- Internet connection
- Storage permission enabled
- Basic command knowledge

---

## Installing Termux

Install Termux from the official source.

After installation, open Termux and update packages:

---
## Install Basic Development Tools
```md
### Install Git

Git is used to track code changes and upload projects to GitHub.

Install Git:

```bash
pkg install git

---
```md
### Install Nano Editor

Nano is a terminal text editor used to create and edit files.

Install Nano:

```bash
pkg install nano

---

Check Git installation:

```bash
git --version

---
```md
##Install Python
Python allows you to create and run Python applications.

Install Python:

```bash
pkg install python


Check Python:
```bash
python --version

---
```md
##Install Node.js
Node.js allows you to build JavaScript applications.

Install Node.js:

```bash
pkg install nodejs

Check Node.js:

```bash
node --version

---


```md
##Enable Storage Access

Allow Termux to access your phone storage:

```bash
termux-setup-storage

Grant permission when Android asks.

