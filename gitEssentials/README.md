## Git Essentials
[What is git ?](#what-is-git)

[Tracking changes with git](#1-tracking-changes-with-git)

### What is git
Git is a version control software that tracks changes in the files in a codebase or project repository.

- Git stores and manages multiple versions of a project's files, allowing developers to revert back to previous versions if necessary. 
- It also supports parallel developement, which means that multiple people can work on different versions of the project's files (by creating different branches) and merge their changes together.

### 1. Tracking changes with git

#### Step 1: Git user configurations
Basically git is a software, so as a user of it we need to configure with our credentials like name, email etc.

Git configurations can be done in 3 levels, (priority wise shown below)

```--local ``` (default) --> Configurations are applied to the particular repository only.


```--global ```--> Applied to any repository where git is initialized, but only for a particular user of the operating system.

```--system ```--> Applied to any repository where git is initialized and for all users of the operating system.

Example: Global level user configuration
```
git config --global user.name "My name"

git config --global user.email "myemail_id@email.com"
```
Once configured check the configurations
```
git config -l
```
To change the user configuration
```
git config --edit --global
```

Moreover there are other options to configure the git facilities like core-editor, merge tools, color outputs and aliases to git commands.

[Know more about git configurations](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-config)

#### Step 2: Deploy git in a repository

In order to track the changes in a project repository we need to deploy git in that particular repository.

``` git init ```  --> To initialize git in a working repository.

- Normally the project repository is called an working repository and once git is initialized it is called a git repo/local git repository

### Working of git

![Git working](gitWorking.jpg)

- A new file just added to the working_dir --> it is in untracked (```U```) mode. Untracked files are shown in red color on typing 'git status'.

- Then the file is added to the stagging area.

- Then we do modifications and 



### 2. Local to Remote repo in Github

### 3. Collaboration using git