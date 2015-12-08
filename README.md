This is a quick starter for how to create and work with git branching.
	
	Create a new branch
	
	$ git branch branchName

	git branch only creates a new branch with a name that you specify. You are still on your master branch. 

	To get to your newly created branch you have to run the checkout command.

	$ git checkout branchName

	Also if you want to switch back to master it would be 

	$ git checkout master

	!!!!Remember if you have made commits on a branch all the other branches will be behind on commits. Meaning if you are working and making commits on branchName and switch back to branch master it will not have the updated commits you have made to branchName.

	If want to check what branch you are working on.

	$ git branch

	git branch will show what branch you are working on with a star ex( * master) and will also show what branches you have available ex (* master  branchName).