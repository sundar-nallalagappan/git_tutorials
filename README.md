### This is Git tuorials 

Few git commands are as below
git --version

git init - creates a new git repository (initializes empty git repo - .git file)
(if we have not cloned the existing git repo, then git init must be done)


### Configuring steps for first time - set the user name and email id
git config --global user.name "Sundar Nallalagappan"
git config --global user.email "nsundar.1990@gmail.com"

git status - to check the untracked files

git add README.md - git will start tracking this file
git add .         - to track all the untracked files


git commit -m "comments"  --> move the tracked files to staging environment


git branch --> shows the branch

git branch -M main --> To rename my main branch from Master to main (both names should be same)

<For the first time commit only>
git remote add origin https://github.com/sundar-nallalagappan/git_tutorials.git
git remote -v --> check for fetch & pull branch
</>

git push -u origin main  ==> Push the changes to git

# To create new branch
git branch developer1 --> to create a new branch called developer1 (copy of main)

git checkout developer1 --> to swicth to branch

from main branch ==> git merge developer1 (to merge the changes from branch to main)




####### 

