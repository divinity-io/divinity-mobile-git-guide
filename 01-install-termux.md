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


##Install Basic Development Tools

Install Git:
pkg install git

Install Nano editor:
pkg install nano

Check Git installation:
git --version

##Install Python
Python allows you to create and run Python applications.

Install Python:
pkg install python


Check Python:
python --version

##Install Node.js
Node.js allows you to build JavaScript applications.

Install Node.js:
pkg install nodejs

Check Node.js:
node --version

##Enable Storage Access

Allow Termux to access your phone storage:
termux-setup-storage

Grant permission when Android asks.


```md
```bash
pkg update && pkg upgrade
