# git commmands 

+ **git**

  git is used for each git command and always comes first
---
+ **version**

  Displays the version of git that is installed
---
+ **repo**

  Short for repositorie
---
### git workflow

Working Directory | Staging Area | .git Repo | Github Repo
--- | --- | --- | ---
local | local | local | remote
1 (add -->) | 2 (commit -->) | 3 (push -->) | 4 DONE!

1. If you have created a new file or folder you can add it to the **Staging Area** with **add <file/folder>**

2. From the Staging Area you want to commit your file/folder to the git repo, with **commit <file/folder>** you can do so. However NANO will open to add your commented text, to avoid this you can use the **-m** flag to write a inline comment

3. When your files/folders are in the repo you can you can then **push** them remote (Github)

4. Now your fles and folders are online
---
+ **status**

  Will show the status of your working tree. Here you can see if there are any files left in the pipeline
---
+ **init**
  
  If you have a file on your computer and you want to have git tracking it you use this command
---
+ **unzip**

  Unzip folders in git
---
+ **pull**

  pull the latest version from the repo to see if it is updated with your own
---
+ **branch**

  A branch is something you create when you want to work on your project but don't want to excecute those changes right away.

  git **branch -a** Shows working branch and all other branches
  
  git **branch <branchname>** Creates a new branch 
  
  git **branch -m <branchname> <newbranchname** Changes the name of the branche
  
  git **branch -d <branchname>** deletes branch
---
+ **log**

  Shows you the history of the branch.
  
  Use **git log --oneline** for each commit to be on "oneline"
---
+ **checkout**

  Switch branches.
  
  Use **git checkout -b <branchname>** to create a branch and enter it.
---
+ **diff**

  Look for the differences between the branch and master branch.
---
+ **merge**
  
  merge you branch back into the master branch.
