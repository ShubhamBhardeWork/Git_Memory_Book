# Git 
## Pre-Requisites:-
- Download & Install Git from browser. 


## What is Git:-
- Git is a Distributed Version Control System (DVCS).

- It helps developers track changes made to files and source code.

- Git was created by Linus Torvalds in 2005.

- Git is free, open-source, fast, efficient, and scalable.


## Why Git:-
- Track changes in source code.

- Manage multiple versions of a project.

- Collaborate with multiple developers.

- Roll back to a previous version whenever needed.

- Create separate branches for new features.

- Merge completed work back into the main branch.


## Git Configuration:-
Configure our Git identity before making commits.

```sh
git config --global user.name <user name>
git config --global user.email <email id>
```

### Verify Configuration:-
```sh
git config --global user.name
git config --global user.email
git config --list
```


### Check git version:-
```sh
git --version
```

### Remove Git Repository:-
1. using manually you can ```delete .git folder```
1. using linux command:-
    ```sh
    rm -rf .git
    ```


## Git Commands:-
1. git init
1. git status
1. git remote -v
1. git diff  

    git diff --staged

    git diff < file-name >

    git diff < commit-1 > < commit-2 >

    git diff < branch-1 > < branch-2 >

1. git log

    git log --oneline
    
    git log --oneline --graph --all

1. git add .

    git add < file-name >

1. git commit -m < message >
1. git commit -a -m < message >
1. git commit --amend -m < new-message >
1. git branch 
    
    git branch -v

1. git branch < branch-name >
1. git branch -M < branch-name >
1. git branch -d < branch-name>
    
    git branch -D < branch-name>

1. git checkout < branch-name >
    
    git switch < branch-name >

1. git checkout -b < branch-name>
1. git remote add origin < repository-url >
1. git push
    
    git push -u origin < branch-name >
1. git clone < repository-url >
1. git fetch 
1. git pull
1. git merge < branch-name >
1. git rm --cached < file-name >
1. git reset

    git reset HEAD~1

    git reset HEAD
