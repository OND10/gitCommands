
# Git Commands <img width='45' height='50' src='https://image-url.com/git-icon.png' alt='gitImage'> 


🎉 First of all, thanks for taking the time to read this blog! 🎉


### Collaboration between team members during development and provide a powerful and flexible framework for version control.

## ⭐ How it works

##### Create an empty repository:

`` git init`` 

<br />

##### set your name and email :
`` git config --global user.name "your name"`` 
<br />
`` git config --global user.email "email@example.com"`` 

<br />

##### link your local repo. with github a repository : (only if you have an empty repository on github and you are the first one to add things to it) :
`` git remote add origin (link of your repository on github)`` 

<br />

##### To confirm Changes :
- frst adding them to stagging area :
  `` git add .`` 
  
- then commit with a suitable commit message :
`` git commit -m "your commit message"`` 

<br />

##### to view commits log (history)  :
`` git log`` 

<br />

##### to push your commits to the github repository :
`` git push origin master  (or branch name instead of master)`` 

<br />

##### to download the repository to your pc (cloning) :
`` git clone http............ (link of the repo.)`` 


<br />

#### ((don't type (git remote) as you have the remote already after cloning !!))

<br />

##### to pull the latest update from github to your computer ##### :
`` git pull origin master (or branch name instead of master)`` 
<br />

##### if you coded with full of wrong codes and needed to rollback your changes to the last comment :
`` git reset --hard`` 
<br />

<hr style='height:20px;color:grey;'>

### Branches 
 
#####  to view the current branch #####
`` git branch`` 


##### create a new branch and switch to it#####:
`` git checkout -b (branch name) `` 

<br />
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

#### 🔴🔴 Please do not work with your teammates on the master branch 🔴🔴
<br />
#### 🔘🔘 Solution to make another branch and should be named as develop to work on it 🔘🔘


<h4 style='text-align:center'>  Hope you are coding well with 🖤 </h4>



