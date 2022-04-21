# Version Control in Git/Github for Gahlmann Lab

### A walkthrough of how to use Git/Github together

# Background

We will be doing all of our commands and pushes in the command line. There are GUI tools available but you will eventually run into a situation that you need the command line tools to do. 

First, a little background.

**Git** - Git is a version control software installed on your local machine

**Github** - Github is a for-profit company now owned by Microsoft. Github offers web based hosting for software and code repositories.

**Distributed Version Control** - Git is a distributed version control system. This means that there is not one master copy of the repository. Every developer who checks out the repository has a complete record of the project including all changes to the code. 

**Repository (repo)** - the basic unit in git. This is a record of all changes to specified files in your project.

**Fork** - personal copy of another user's repository

**Branch** - a parallel version of a repository. The top level branch of a repository is not called 'main', formerly called 'master'. 

# Setup

You must be set up with git/github before you are able to use them. 

### Mac/Linux users
Git comes with your operating system. No installation required.

### PC users
Need to install git and git bash. Watch the first 2:45 of this video: [https://www.youtube.com/watch?v=albr1o7Z1nw](https://www.youtube.com/watch?v=albr1o7Z1nw)

### Create GitHub account
Create a free account here: https://github.com/

# Scenario 1: Git Basics

Let's walk through a basic scenario where you have just installed git and github and are using it for the first time

#### Git configuration
Check your git version
```
git --version
```

Set up your config variables
```
git config --global user.name "Your name"
git config --global user.email "Your email"
```

### Clone existing Github repository
This is in the situation that you will be working from an existing Github repository. If you are just starting a new project, I recommend creating an empty repository first in Github.

```
git clone <url> <where to clone (optional)>

ex:
git clone 
```