# 1. cloning form github web
## commands :
 1. git clone ' paste https repo link'
 2. git add filename or git add . --> adds every new file created
 3. git status --> gives complete status description like new files changed files etc.
 4. git commit -m "type commit message"
 5. git branch -M main --> initializing master branch as 'main'. // nothing //
 6. git push origin main --> pushes to origin main branch of clones repo. but verifies crenditials

------------------------------------------------------------

# creating repo in local machine and hosting it on github
1. create a folder
2. create files
3. git init --> initializing folder to git
4. git add .
5. git commit -m "commit message"
6. now add remote origin using ssh link
7. git remote add origin " ssh link"
8. git push -u origin main --> -u=upstreaming

# Branching
1. The main branch is the master branch for every file and their commits.
2. git branch --> gives the info about all branches and *branch for the branch currently in use.
3. git checkout bname to change form one B to another B
4. to create a new brach use git checkout -b subranch --> -b cmd will create a new branch
5. must add the files to new branch git add .
6. them commit the changes git commit -m "updated changes to subranch"
7. git push origin subranch 

## pull request pr is pulling downloading repo from github or pulling code from other branch to main branch
## add and commit --> git commit -am "updated"

# Merging branches
1. after commiting and pushing all changes to github  to new branch
2. do compare and pull request 
3. now changes and complete code is merged in github git merge dummy
4. now we have to pull request from main to local machine
5. git pull origin main
6. now we can delete the branch 
7. git branch -d dummy

# undo / reset
1. staged = add cmd to git to track the changed
2. after commiting if you want to uncommit or unstage use
3. git reset --> reset last change or unstage
4. to uncommit use git reset HEAD/ HEAD~1
5. head~1 takes last commit and before change ie staging file
6. it will reset all commits

# forking
1. forking means duplicating entire repo form a person to our github
2. now we can make changes
3. add content make commits