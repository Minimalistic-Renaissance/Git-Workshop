##Commads For Settig Up Git :


	git config --global user.name "your Nmae Here"				//For setting up the your user name....//
	git config --global user.email "Your Email Here"			//FOr setting up the your email id...//


##Basic Commands :


	git init								//To initialise your folder a repository..//
	git add .								//For making the git to watch your work...//
	git commit -am "your Commit Message"	//To save your work with a message...//



##Rollback Commands :


	git checkout .				    //For going to last stable commit.....//
	git reset --hard CommitID		//For going to a specific commit specified by the commit number...//


##GitHub Commands :

	git init
    git remote add origin <my shh repo>					//For specifying your master.....//
	git config branch.master.remote origin && git config branch.master.merge refs/heads/master
	git pull origin master				//To pull all the work from github or from any dedicated server...//
	git push origin master
			 							//To push your work on github or on any dedicated server...//
##GitHub Commands (cloning) :

 	git clone <git ssh url>

##General Commands :

    git status 								//gives the cur state of repository....//
	git log									//To see all the commits with details.....//
