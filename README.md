# Project_4DML

##TASK


1.	Install Git Bash.
2.	Initialize a new local repository.
-	cd <project_name>
-	git init
3.	Create a README.md file and put a few lines in there using Markdown syntax. Commit changes to master branch.
-	echo “<text>” > README.md
-	git add README.md
-	git commit -m “commit message”
4.	Create 3 versions of master branch with names feature_a/b/c.
-	git checkout -b feature_a
5.	Make different changes in each branch and commit them.
-	git add .
-	git commit -m “commit message”
6.	Merge changes from all feature branches to feature_d branch.
-	git checkout -b feature_d
-	git add .
-	git commit -m “
-	git merge feature_a
-	git merge feature_b
-	git merge feature_c
	
7.	Merge feature_d to master.
-	git checkout master
-	git merge feature_d
8.	Check if you have all changes in master branch.
-	git branch –merged
-	git status
9.	Check what was changed and what was added commit by commit. You could play more with branches and code changes in your local repo to be more familiar with the background processes of Git.
-	git log
10.	Set up a git remote, pointing to your gitlab/github account. Push the changes and make sure they're accessible for the team.
-	git remote add origin <repository_url>
-	git remote -v
-	git push --set-upstream origin main
