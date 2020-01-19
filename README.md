# learngit
Set up a git repository and start pushing and pulling files
-----------------------------------------------------------

Step 1: Create a Repository using the website

Step 2: Add  Repository (ex Github repo)
>>> git remote add origin <repository-link>

Step 3: Create a local repo 
>>> git init  (for initializing a local folder as git repo)
>>> git status (for checking status)
>>> git add . (for adding files in to staging area)
>>> git commit -m "message" (for commiting the  files)
>>> git push -u origin master (for pushing files into remote repo)
>>> git pull origin master (for pulling files from remote repo)

REMOVE REMOTE (LOCAL)
---------------
git remote rm remote_name

CREATE NEW BRANCH
-------------------
git branch branch_name
git checkout branch_name

DELETE BRANCH
--------------
local:
git branch -d test

remote:
git push origin --delete test

