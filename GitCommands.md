##Commads For Settig Up Git :

	git config --global user.name "your Nmae Here"				//For setting up the your user name....//
	git config --global user.email "Your Email Here"			//FOr setting up the your email id...//
	git init								//To initialise your folder a repository..//

##Basic Tracking Commands :
	
	git add .								//For making the git to watch your work...//
	git commit -m "your Commit Message"	//To save your work with a message...//

##Branching Commands
	
	git branch 						//Shows all the branches in the repo...//
	git checkout -b branch_name		//makes a new branch with the specified name at the given stage...//
	git branch -d branch_name		//safe - dose'nt delete branch if uncommited changes exist
	git branch -D branch_name		//unsafe - force delete a branch....//

##Merging Commands 
	
	git checkout master				//swithes to master...//
	git merge branch_name			//Merge branch features to master

##Rollback Commands :

	git checkout .				    //For going to last stable commit.....ignoring untracked changes....//
	git reset --hard CommitID		//For going to a past commit PERMANENTLY....//

##Sync with GitHub :

	git init
	git add .								//For making the git to watch your work...//
	git commit -m "your Commit Message"	//To save your work with a message...//
    git remote add origin <my shh repo>				//For specifying your master.....//
	git config branch.master.remote origin && git config branch.master.merge refs/heads/master
	git pull origin master							//To pull all the work from github or from any dedicated server...//
	git push origin master
			 							            //To push your work on github or on any dedicated server...//
##GitHub Commands (cloning) :

 	git clone <git ssh url>
 	git chekout master

##General Commands :

    git status 								//gives the cur state of repository....//
	git log									//To see all the commits with details.....//
	git log --oneline --all 				//one line pretty logs
	git log -p 								//shows diffrence between the current and past commit 
