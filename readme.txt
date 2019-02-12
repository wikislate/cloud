
------------------------------------------------------------GIT ADVANCE--------------------------------------------------------------


git diff --staged	# Difference between staged and last commit.
git diff		# Difference between working copy and staged.

git commit --amend -m "message"		# Changes last commit.

git reset HEAD
git reset --soft HEAD	# Removes file from repo but remains in staging area.
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
