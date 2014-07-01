funWithGit
==========

This is a project Repo. You can add unlimited project repos with one GitHub account. You can automatically generate a website for your project by using GitHub Pages. Or manually just create a new 'gh-pages' branch.

# GIT Shell
### clone a remote repo into local
git clone https://github.com/user/hello-git.git

### view all branches (local & remote)
git branch -a

### clone a remote feature branch into local
cd hello-git

git checkout -b pmud1234_feature_branch origin/pmud1234_feature_branch

### create the feature branch locally
git checkout -b pmud1234_feature_branch master

### immediately push to origin and track it
git push -u origin pmud1234_feature_branch

### updates from origin
git fetch origin

git checkout master

git merge origin/master

git checkout pmud1234_feature_branch

git merge -m "PMUD-0000 merge from master" master

### updates from origin(2)
git checkout master

git pull

git checkout pmud1234_feature_branch

git merge -m "PMUD-0000 merge from master" master

### commit to the feature branch
git checkout pmud1234_feature_branch

git add .

git status

git commit -m "PMUD-???? some useful commit message"

### push the feature branch into the origin repo
git checkout pmud1234_feature_branch

git push

### merge a branch back to master
git checkout master

git merge --ff-only pmud1234_feature_branch master

### push to origin repo from current branch
git push

### remove all deleted tracked files
git add -u .

# Testing History
* 10:47 PM 22/04/2014

played with Git Shell in Windows. Works quite similar to under Linux, Cool!

* 8:55 PM 25/06/2014

tried to contact with GitHub using Linuxmint at the office box, but failed because of the http proxy:-(
