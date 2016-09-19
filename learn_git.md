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


* Discard changes in working directory

	```
git checkout HEAD filename
	```

* Unstage file changes in the staging area

	```
git reset HEAD filename
	```

* Reset to a previous commit in your commit history

	```
git reset SHA(7 chars) 
	```



* List all of a Git project's branches

	```
git branch
	```

* Create a new branch

	```
git branch branch_name 
	```

* Switch from one branch to another

	```
git checkout branch_name
	```


* Join file changes from one branch to another

	```
git merge branch_name
	```



* Create a local copy of a remote

	```
git clone
	```


* List a Git project's remotes

	```
git remote -v
	```


* Fetch work from the remote into the local copy

	```
git fetch
	```


* Merge origin/master to your local branch

	```
git merge origin/master
	```


* Push a local branch to the origin remote

	```
git push origin <banch>
	```



### Git collaboration steps:
  1. Fetch and merge changes from the remote
  2. Create a branch to work on a new project feature
  3. Develop the feature on your branch and commit your work
  4. Fetch and merge from the remote again (in case new commits were made while you were working)
  5. Push your branch up to the remote for review
  
