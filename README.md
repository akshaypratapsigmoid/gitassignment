# gitassignment
My Git Assignment
Making change from Feature_1 branch
1st change in Feature_2
Rebase step
Again making changes from Feature_1
Merged conflict for Feature_1
Change made in HotFix branch

## Step 8: Proper README for the "Git_Assignment" repository

- Created a directory _Git_Assignment_ at the desktop and initialized a git repository inside this directory using "git init ." command.
- Now we were on the master branch. Then created two branches _Integration_ and _HotFix_ using "git checkout -b \<branch-name>" command.
- Created two sub-branches, _Feature_1_ and _Feature_2, from the __Integration_ branch.
- Then created new remote repository on github.com with a _README.md_ file.
- Set both, the _master_ branch of local repository and _origin/master_ branch of the remote repository to track each other, where _origin_ is the     reference for the remote repository.
- Pushed _Integration, __HotFix, __Feature_1_ and _Feature_2_ branches on the remote repository and set them up with _origin/Integration,         __origin/HotFix, __origin/Feature_1_ and _origin/Feature_2_ branches to track each corresponding branch.
- Pulled all the changes from remote repository to the local repository, to bring down the _README.md_ file.
- Switched to the _Feature_2_ branch on the local side and made some changes to the _README.md_ file.
- Pushed the changes made in local _Feature_2_ branch to the _origin/Feature_2_ branch.
- Created pull request for the changes in _origin/Feature_2_ branch to be reviewed by two reviewers Mahesh and Karan, and be merged into                     _origin/Integration_ branch. 
- Deleted the _Feature_2_ branch locally and pushed this deletion to the remote repository for removing its stale reference _origin/Feature_2_ using     "git push origin :/<branch_name>".
- Switched to the _Feature_2_ branch locally and made some changes in the _README.md_ file and rebased it to the local _Integration_ branch, resloved   merge conflicts using _p4merge_ mergetool, commited those changes to the _REDAME.md_ file which was one of the two given options from "git add/rm       /<conflicted_files>" and used the command "git rebase --continue" to move forward with rebase successfully.
- Created two different pull requests remotely for _origin/Integration_ to be reviewed by two reviewers and be merged into the _origin/HotFix_ and the   _origin/master_ branches.
- Switched to the _Feature_1_ branch on the local side and made some changes to the _README.md_ file.
- Pushed the changes made in local _Feature_1_ branch to the _origin/Feature_1_ branch.
- Created three different pull requests for the changes in _origin/Feature_1_ branch to be reviewed by two reviewers Mahesh and Karan, and be merged into   _origin/Integration, __origin/HotFix, __origin/master_ branches . 
- Deleted the _Feature_1_ branch locally and pushed this deletion to the remote repository for removing its stale reference _origin/Feature_1_ using     "git push origin :/<branch_name>".
- Switched to the _HotFix_ branch on the local side and made some changes to the _README.md_ file.
- Pushed the changes made in local _HotFix_ branch to the _origin/HotFix_ branch.
- Created two different pull requests for the changes in _origin/HotFix_ branch to be reviewed by two reviewers Mahesh and Karan, and be merged into       _origin/master_ and _origin/Integration_ branches.

_NOTE: __master_ branch on the local side and _origin/master_ branch on the remote side refers to the _Production_ and _origin/Production_                 branches on the local and remote repository respectively.

## Screenshot_ for the "git hist" command:
<img width="635" alt="Screenshot 2023-01-26 at 10 54 00 PM" src="https://user-images.githubusercontent.com/123646244/214906421-d022c519-321a-4743-8fe0-871385728507.png">

