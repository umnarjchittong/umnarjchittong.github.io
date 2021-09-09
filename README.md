# umnarjchittong.github.io

git init //Initialize a Git Repo
git status //See What Branch You're On
git branch //To see local branches
git branch -r //To see remote branches
git branch -a //To see all local and remote branches
git checkout -b my-branch-name //Create a New Branch
git checkout my-branch-name //Switch to a Branch In Your Local Repo
git pull //Switch to a Branch That Came From a Remote Repo
git checkout --track origin/my-branch-name //Switch to a Branch That Came From a Remote Repo
git push -u origin my-branch-name //Push to a Branch
git push //If your local branch already exists on the remote

#Merge a Branch
git status
git checkout master-branch-name //changes will be merged into this branch
git merge my-branch-name //merge another branch into the current branch

#Delete Branches
git push origin --delete my-branch-name //delete a remote branch
git branch -d my-branch-name //delete a local branch

pull repo, goto new folder
git init
git stataus
git pull https://github.com/umnarjchittong/link.git //Get git
git branch -a //To see all local and remote branches
git checkout --track origin/v_1.5g
