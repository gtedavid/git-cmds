# git-cmds

Help for Git Commands - FR & EN version - WIP

## ENGLISH

### First steps

#### Option 1 - Initiate a repository

```powershell
git config --global user.name <user_name>

git config --global user.email <user_email>

git init <project_name>
```

#### Option 2 - Clone a repository

Head to an empty folder.

Type :

```Powershell
git clone <url>
```

If the main branch isn't the one you're looking for then, type:

```Powershell
git checkout <branch_name>
```

### Post initialization

#### Creating a new branch

If the main branch isn't the one you're looking for, and you want to create a new branch, type:

```Powershell
git checkout -b <branch_name>
```

#### Steps to commit and push - WIP

1. add files

`git add .` -> add all modified files to be commited

OR

`git add <file1> <file2> <file3>` -> add file1, file2, fileX..... to be commited.

2. Commit with message (2 levels)

`git commit` -> you will be asked to add a message via a "vi" integrated editor in your terminal (Visual Studio Code)
[More on VI commands](https://github.com/gtedavid/cmd-tips-linux/tree/vi-commands).

OR

`git commit -m"Title of changes"` -> Adds a brief description about the commit

`git commit -m"Title of changes" -m"description"` -> Adds a brief description about the commit and a description.
You can make the description longer by not entering the second `"` and pressing `Enter` to go to the line if needed.

3. git push _WIP_

###########  WIP  ###################
