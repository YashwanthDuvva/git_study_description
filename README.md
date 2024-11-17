# 1. cloning form github web
## commands :
 1. git clone ' paste https repo link'
 2. git add filename or git add . --> adds every new file created
 3. git status --> gives complete status description like new files changed files etc.
 4. git commit -m "type commit message"
 5. git push origin main --> pushes to origin main branch of clones repo. but verifies crenditials

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