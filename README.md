## Basic git Commands

### 1. Push files to your git repository

```git init
   git status
   git add .
   git commit -m "<write message>"
   git remote add origin <your git https link>
   git push -u origin master
```
### 2. Clone a repository

```git clone <git repo HTTPS link>
```
### 3. Pull changes to your local repository

```git pull origin master
```
### 4. Check all the remote repository

```git remote -v
```
### 5. Remove a remote location

```git remote rm <git repo HTTPS link>
```
### 6. Check branch

```git branch
```
### 7. Create branch

```git branch <branch name>
```
### 8. Checkout another branch

```git checkout <branch name>
```

### 9. Delete local branch

```git branch -d <branch name>
```
### 10. Delete remote branch

```git push origin --delete <branch name>
```
