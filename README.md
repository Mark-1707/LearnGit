# LearnGit


#### Used to chek the installed git version
git --version

#### Config your github account
git config --global user.name "Omkar Rjendra Shirote"
git config --global user.email "shiroteomkar6@gmail.com"

#### Display user information after config
git config --global user.name
git config --global user.email

#### You can directly edit the configuration in file
git config --global --edit 

#### Create a new Repository or make a directory as a repository
git init

#### shows file which is being tracked by git
ls -a

#### Show the changes in the repository
git status

#### First track the file and then commit
git add <filename>
#### this adds the file in staging area
#### files in staging area can be committed

#### Commit
git commit -m "initial commit"

#### Check no. of commits and other information about the commits
git log

#### Perform operation on all files
git add .

#### Go to required commit
git checkout <commit hash code/branch name>

#### Back to current commit after checkout
git checkout master

#### shows the branch and current branch
git branch

#### Create a new branch
git branch <branch name>

#### Shortcut to create a new branch and switch to it
git checkout -b username/multiply

#### Merge commits between branches
git merge <changed branch>

#### git ignore
touch .gitignore

#### Push repo on github
git remote add origin https://github.com/Mark-1707/Lets-Learn-Git.git

#### push
git branch -M master
git push -u origin master

#### Clone repository
git clone <Link>
