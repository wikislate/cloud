
------------------------------------------------------------GIT ADVANCE--------------------------------------------------------------


git diff --staged	# Difference between staged and last commit.
git diff		# Difference between working copy and staged.

git commit --amend -m "message"		# Changes last commit.

git reset HEAD
rit reset --soft HEAD	# Removes file from repo but remains in staging area.
git reset --hard HEAD	# Removes file from everwhere. Everything gets cleaned.

git commit --amend	# Decreases the no. of commits, when added file many times
			# by changing the commit.

git branch branchname	# Creates branch
git checkout branchname	# Shifts the working branch.

git checkout master	# Checkout to master and merge the branch made into
git merge branch	# master

git rebase -i HEAD~n	# Edit no. of commits by providivg option

git rm --cached file	# Delete commited file from repo. Keeps in local.
git rm file		# Delete from repo as well as local.

git push -u 		# Adds remote upstream to branch. Use this when you first make a push in branch.
git push		# Sends data to repo
git pull		# Updates your local

git fetch		# Updates local without creating merge commits.
git rebase		# Squeeze no. of commits to single one
git rebase --continue	

git remote -v			# Checks remote
git remote add origin branch	# Adds remote origin to branch

git tag tagname -m "message"	# Creates tag
git push tags			# Push tags

