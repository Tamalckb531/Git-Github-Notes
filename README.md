# Git-Github-Notes

Git and Git-Hub notes with Open Source Tips

<hr/>

# Basic Terminologies :

1. To check git version :
   > git --version
2. To check the condition of git repository :
   > git status
3. git configure file (list for check and other two for set) :

```
git config --global user.email "email"
git config --global user.name "name"
git config --list
```

4. To add a folder in git repo and start track it :

   > git init

5. To add git folder in staging area :
   > git add .
6. To commit :
   > git commit -m "message"
7. To see the history of commit :
   > git log
   > git log --oneline (to get the history in one line)

# Git branch and conflict :

1. To check current branch
   > git branch
2. To create new branch
   > git branch new-branch
3. To switch into a branch
   > git switch branch-name
   > git checkout branch-name
4. To merge another brunch code in a branch
   > git merge branch-name
5. Delete branch :
   > git branch -d branch-name

# Git diff, stash and tag :

1. To check comparison between two file :
   > git diff
2. To go to another branch with out add (a temp saving method) :
   > git stash
3. To use a version tag :
   > git tag tag-name
