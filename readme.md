# git notes

```
git init							# makes current folder a git repo
git add <filename>					# stages one file
git add -A							# stages all non-ginored files
git commit -m '<msg>'				# commit
git checkout -b <branchName>		# creates new branch and puts you in the branch
git checkout <branchName>			# puts you in the branch
git status							# uncommited changes / current branch
git merge <branchName>				# merges commits from other branch
git log								# show history of comits
git blame							# who commited what line
git reset --hard <optional id>		# go back in time
git tag -a '<semver>' -m '<msg>'	# add tag to current commit
git tag								# list all tags
git reflog							# last 15 git actions
git remote  add <origin> <url>		# one time connect to github
git push origin <branch>			# sync local to remote
git pull origin <branch>			# sync remote to local (merge)
```

> other notes

```
clear
```