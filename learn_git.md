# Learn Git Tutorial

## Command line commands:

* Create a new git repository

	```
git init
	```
	
* Inspect the contents of the working directory and staging area
	
	```
git status    
	```

* Add files from the working directory to the staging area

	```
git add file 
	```
	
* Show difference between working directory and staging area

	```
git diff
	```
	
* Permanently store file changes from the staging area in the repository

	```
git commit
	```

* Show a list of all previous commits

	```
git log
	```

git checkout HEAD filename  - Discard changes in working directory
git reset HEAD filename     - Unstages file changes in the staging area
git reset SHA(7 chars)      - Can be used to reset to a previous commit in your commit history

git branch                - Lists all a Git project's branches
git branch branch_name    - Creates a new branch
git checkout branch_name  - Used to switch from one branch to another
git merge branch_name     - Used to join file changes from one branch to another

git clone               - Creates a local copy of a remote
git remote -v           - Lists a Git project's remotes
git fetch               - Fetches work from the remote into the local copy
git merge origin/master - Merges origin/master to your local branch
git push origin <banch> - Pushes a local branch to the origin remote

### Git collaboration steps:
  1. Fetch and merge changes from the remote
  2. Create a branch to work on a new project feature
  3. Develop the feature on your branch and commit your work
  4. Fetch and merge from the remote again (in case new commits were made while you were working)
  5. Push your branch up to the remote for review
  
