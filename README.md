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

#### git --version

#### create new repo on command line. 

echo "# learning-git" >> README.md
// create the readme.md file on local machine.

git init
// initialize .git file to the folder to track changes.

git add README.md
// push the readme.md file on the github repository.

git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SakarSrivastava/learning-git.git
git push -u origin main

#### push an existing repository from the command line

git remote add origin https://github.com/SakarSrivastava/learning-git.git
git branch -M main
git push -u origin main