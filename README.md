# HOW_TOs


git clone: git clone ssh://git@ssh.github.com:443/BhaviD/SE_Project.git

TO CHECK FOR BRANCH : git branch

TO SWITCH TO NEW BRANCH: git checkout -b <branch-name>

TO ADD: git add . (add all)

TO PUSH: git push (to branch)

TO SWICH BRANCH : git checkout <branch-name>

TO LIST ALL REMOTE BRANCHES: git branch -a

TO CHANGE NAME OF BRANCH: git branch -m <new-name>

TO CREATE A NEW BRANCH :git branch <branch-name>   (doesn't checkout new branch)

TO DELETE SPECIFIC BRANCH: git branch -d <branch-name>

creating a branch


TO CREATE AND CHECKOUT NEW BRANCH: git checkout -b <new-branch>

TO CHECKOUT THE REMOTE BRANCH LIKE A LOCAL BRANCH: git fetch --all

			# Start a new feature
				git checkout -b new-feature master
			# Edit some files
				git add <file>
				git commit -m "Start a feature"
			# Edit some files
				git add <file>
				git commit -m "Finish a feature"
			# Merge in the new-feature branch
				git checkout master
				git merge new-feature
				git branch -d new-feature



TO LEARN MORE ABOUT GIT :https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud

