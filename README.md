This is reminder of the commands we learned in class so far
* git init -> to create a new repo on our local directory(current folder)
* git clone branch_name -> to copy the repo from remote to your local. It also creates the set up config to the remote repo.
* git checkout -> for connecting to a branch
* git checkout -> branchname -> for creating new branch or to switch to diffrent branch
* git add . -> If it have . it's to add all files to current branch
* git add filename -> to add one file to current branch
* git commit -m "xxxxxxx" -> save changes to brach with comment, it is always good to add comment for your teams to know what you did.
* git status -> To view all the changes we made to branch/folder so far. it let us inspect the working directory and the staging area,
* git push origin branchname-> Push to remote git repo, this time we need to creat a pull request on the github and then merge it. You can     merge it your self or anyone can merge our file. 
* git push origin master -> If we directly push it to the master/main file we don't need to deal with pull request then merge. 
* git pull origin branchname -> getting latest changes from remote repo.
* git log -> displays commited history, it let us filter it and search specific changes
* git push -u -> to push changes from any local branch
* git restore --stage file-name -> to restore staged file from local
* git restore "file name" -> replace edited or deleted file to its original
* git branch -d branch name ->to delete specific branch if it has merg
* git branch -D branch name -> to delet all
