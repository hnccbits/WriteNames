# About this repository

This repository to practice common git concepts. Everyone should have git installed and a github account running.
This task should be done by 10pm, 06-04-2020.

## Concepts 

* _Git Forks_
* _Git Branches_
* _Git commits_
* _Pull Requests_

Follow the instructions to complete this task.

### Step 1 (Make your own fork)

* Click the fork button on top right hand corner of this page. This will make a copy of this repository in your account.
  You just created a fork.

* Go to your fork and clone it.
  
  `git clone your-fork-git-link`

* Go into your cloned repo using `cd` in git bash.
  
  `cd your-fork-folder`

### Step 2 (Make a branch)

* Create a new branch using 
  
  `git checkout -b your-branch-name`

   You have created a new branch. You will now make changes in this branch.

### Step 3 (Make your commits)

* There is folder named HnCC-2019-members.
  
  `cd HnCC-2019-members`
  
* Make a file `your-name.txt` and write your name and branch.

* Commit your changes using
  
  ```bash
  git add your-name.txt
  git commit -m "My Name"
  git push --set-upstream origin your-branch-name
  ```

  Enter your github credentials and push.

### Step 4 (Create a Pull Request)

* Go to original repo and make a pull request.
