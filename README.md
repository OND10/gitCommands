# Git Commands <img width='45' src='https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png' alt='git Image'> 


🎉 Welcome to this guide on Git commands, thanks for taking the time to read this blog! 🎉

## 🤔 So what is git?

Git is a version control, it is a powerful tool for collaboration among team members during development. It offers a flexible framework for version control, allowing seamless coordination and management of project changes.

## ⭐ How Git Works
Read [this to](how-git-works.md) understand how Git works.

## ⏩ Quick Start Guide

### Create an Empty Repository:

```bash
git init
```

### Configure Your Name and Email:

```bash
git config --global user.name "Your Name"

git config --global user.email "email@example.com"
```

### Link Your Local Repository with a GitHub Repository:

(Only necessary if you have an empty repository on GitHub and you're the first contributor)

```bash
git remote add origin <link_to_your_repository_on_github>
```

### Confirming Changes:

- First, add changes to the staging area:
  ```bash
  git add .
  ```
  
- Then, commit with an appropriate message:
  ```bash
  git commit -m "Your commit message"
  ```

### Viewing Commit History:

To view commit history:
```bash
git log
```

### Pushing Commits to GitHub:

To push your commits to the GitHub repository:

```bash
git push origin master  (or branch name instead of master)
```

### Cloning a Repository to Your PC:

To download the repository to your PC (cloning):

```bash
git clone <repository_link>
```

### Pulling the Latest Updates:

To pull the latest updates from GitHub to your computer:

```bash
git pull origin master (or branch name instead of master)
```

### Rolling Back Changes:

If you need to revert to the last commit due to errors:

```bash
git reset --hard
```

---

## Branches 
 
###  to view the current branch

```bash
git branch
```


### create a new branch and switch to it:

```bash
git checkout -b (branch name)
``` 

--- 

## 🎨 Features

- **History Tracking**: Git allows developers to track changes made to their codebase over time.
* **Branching and Merging**: Git enables developers to work on multiple features or fixes simultaneously by creating branches.
* **Collaboration**: Git facilitates collaboration among multiple developers working on the same project.
* **Remote Repositories**: Git supports remote repositories hosted on platforms like GitHub, GitLab, or Bitbucket.
* **Distributed Development**: With Git, each developer has a complete copy of the repository, including its entire history.
* **Reverting Changes**: Git provides mechanisms to undo changes, whether it's reverting to a previous commit, discarding uncommitted changes, or resetting the repository to a specific state.
* **Conflict Resolution**: When multiple developers make changes to the same file or code snippet, Git helps identify and resolve conflicts during the merging process.
* **Code Review**: Git integrates with code review tools and workflows, allowing developers to review each other's changes before they are merged into the main codebase.
* **Automation and Integration**: Git can be integrated with various tools and services through APIs and hooks, enabling automation of tasks such as testing, deployment, and issue tracking.
* **Automation and Integration**: Git can be integrated with various tools and services through APIs and hooks, enabling automation of tasks such as testing, deployment, and issue tracking.
* **Open Source Ecosystem**: Git is open source and has a vibrant ecosystem of tools, extensions, and community support.

### 🔴🔴 Please do not work with your teammates on the `master` branch. 🔴🔴

### 🔘🔘 Solution: make another branch and should be named as develop to work on it 🔘🔘


<h4 style='text-align:center'>  Hope you are coding well with 🖤 </h4>
