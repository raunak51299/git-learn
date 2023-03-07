# git

- git init 
    - (it will create a .git folder)
- git status 
    - (it will show the status of the folder)
- git add file.text (git add .) 
    - (it will add the file to the staging area)
- git commit -m "message" 
    - (it will commit the file to the local repository)
- git remote add origin 'site' 
    - (it will add the remote repository)
- git branch -M main 
    - (it will change the branch name to main)
- git push origin main 
    - (it will push the code to the main branch)
- git diff 
    - (it will show the difference between the files)
- git log 
    - (it will show the log of the commits)
- git pull origin main 
    - (it will pull the code from the main branch)
- git rebase --continue 
    - (it will continue the rebase)
- git checkout -b branchname 
    - (it will create a new branch)
  
# branch
# Add the remote, call it "upstream":

- git remote add upstream https://github.com/whoever/whatever.git

# Fetch all the branches of that remote into remote-tracking branches

- git fetch upstream

# Make sure that you're on your master branch:

- git checkout master

# Rewrite your master branch so that any commits of yours that
# aren't already in upstream/master are replayed on top of that
# other branch:

- git rebase upstream/master

# pull from branch
- git pull origin branchname
