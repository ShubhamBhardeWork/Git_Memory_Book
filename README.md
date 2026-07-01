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
