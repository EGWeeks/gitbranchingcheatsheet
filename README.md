This is a quick starter for how to create and work with git branching.
	
	Create a new branch
	
	$ git branch branchName

	git branch only creates a new branch with a name that you specify. You are still on your master branch. 

	To get to your newly created branch you have to run the checkout command.

	$ git checkout branchName

	Also if you want to switch back to master it would be 

	$ git checkout master

	!!!!Remember if you have made commits on a different branch the branch master will be behind on commits from the other branches.