# Getting started with Git

## 1. Check if git is already installed 
   ```
   git --version
   ```
## 2. Download and install   
   Download git from [git-scm](https://git-scm.com/download/mac)
## 3. Add email and username to git
   ```
   git config --global user.email"yourGitHub@email.com"
   git config --global user.name"yourGitHubusername"
   ```
## 4. Add file/folders to git - tracking
*Go to the location of the file/folder/project
   ```
   cd /Users/filelocation
   ```
..* Initialize empty Git repository
   ```
   git init
   ```
⋅⋅⋅ --> A hidden folder called `.git` will be generated. If you want to see the folder, you need to 
   ```
   defaults write com.apple.finder AppleShowAllFiles YES
   ```
⋅⋅* Check the status of branch master
```
git status
```
⋅⋅* Include the files to be committed
```
git add <filename>/ git add . / git add *.txt
```
⋅⋅* Commit & show msg (describe the actions done)
```
git commit -m "added text1.txt"
```
⋅⋅* Create 'New Repository' in GitHub
```
git remote add origin <location of the repository>
```
⋅⋅* Push the master
```
git push -u origin master
```

## Other commands
⋅⋅* Show what has been done so far
```
git log
```
