This is first created to register the master branch initially

## head always stands at last commit 

## so lets say we dnt want to publically expose api key so that time to make git not to track what we can do is in the same directory level just create .gitignore and add the file names inside it with extension so it will not be tracked by git

## git ususally dont track empty folders so it will not show 'U' when we simply create a folder ok so when we add any file below the folder it will start tracking it

## So what if i want to track an empty folder... becoz i want to maintain the structure so that time create an folder and inside that folder  creaet an .gitkeep file it is an hidden file it will show so the now the empty folder can also be tracked


-------------This is an edit contributed by master branch-----------

## git checkout was used earlier for switching branches but now they developed a commoand "git switch" becoz checkout was used for many other opertions

## git checkout -b feature_branch_1
## git switch -c feature_branch_1 "-c' means create

## when we created a branch from master then made changes in new branch then in the meanwhile master also made some changes then merging these 2 branches is called 'forward merge/mergecommit'
## wheras when we created a branch from master then made changes in new branch and there is no change made in master then merging these 2 branches is known as 'fast forward merge'

# git rebase is a process of shifting the base (master) so let say we have master and new_branch then we make edits in both and do commits 

## rebase comment 1
