# UIClassDecember-08-2017
To demonstrate on how to use git

To download the project for the first time (clone) cmd : 
	`git clone https://github.com/karthikkrishna611/UIClassDecember-08-2017.git`

To know if some one has made changes to existing code
	`git fetch`
	`git status`

To get the latest changes done by other in the code into your computer cmd:
	`git pull`

To know which file I might have modified or current status of code use cmd : 
	`git status`

To prepare which resources must be sent into the remote repo (server)
	`git add filename1 filename2` to send only selected resources(files)
		or
	`git add .` to send all changes into remote repo

To commit the modified code into local repository
	`git commit -m "commit message(filename:add,delete,modify functionality)"`

To send the modified code from local repository to remote repository
	`git push`
	hi this is sai 

	Sursh Kuma

To create a new branch 
	`git checkout -b branchname`

To go to an existing branch 
	`git checkout branchname`
	Step 1: From your project repository, bring in the changes and test.
git fetch origin
git checkout -b suresh origin/suresh
git merge master
Step 2: Merge the changes and update on GitHub.
git checkout master
git merge --no-ff suresh
git push origin master

changes 
