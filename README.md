# learning-git

- version control system
- suppose you make an app, initially its 1st version
- then you make some changes, then it is second version.
- it manages all the versions and can revert back to previous versions.
- revert changes if there are any issues.

## git branching and merging

- it uses branches to work independently on the current version withou affecting the main code base.
- then you can merge the branch in main code base.
- helps to collaborate, manage the code with other peoples effectively.

## git and github

- git is the command line tool used for version control system in local machine.

- github is web application used to collaborate with other peoples.

- some similar tools are - gitlab, bitbucket etc.


## commands

- git --version

- ls - la

- git status

- git remote -v 
// it tells us on which repo we are going to push the code.

- git branch
// tell the current branch in which code is to be pushed.

## create new repo on command line. 

echo "# learning-git" >> README.md
// create the readme.md file on local machine.

git init
// initialize .git file to the folder to track changes.

git add README.md
// push the readme.md file on the github repository.

git commit -m "first commit"
// save the changes in the files that are added on the git.

git branch -M main
// change the branch to main

git remote add origin https://github.com/SakarSrivastava/learning-git.git
// push the file on the particular repository.

git push -u origin (main) --> if branch is chnaged to main.  
    or
git push -u origin (master) --> name of current branch.



## push an existing repository from the command line

git remote add origin https://github.com/SakarSrivastava/learning-git.git
git branch -M main
git push -u origin main