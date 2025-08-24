Used to practice git.

configuration :
"git config --global user.name USER_NAME"
"git config --global user.email USER_NAME"

adding file to staging area :
"git add filename".

adding file to commit history :
'''git commit -m "commit message"'''

connecting remote repository :
"git remote add origin REPO_URL"

pushing into the remote repo :
"git push origin BRANCH_NAME"

to look difference b/w edited and already commited :
"git diff"

if the edits are staged :
"git diff staged"

to remove stagged file :
"git rm --cached FILE_NAME"

creating new branch :
"git checkout -b BRANCH_NAME"

creating branch using switch :
"git switch -c BRANCH_NAME"

deleting a branch :
"git branch -b BRANCH_NAME"

cloning the remote repo :
"git clone REPO_URL"

pulling changes from remote repo :
"git pull origin main"

tags :

    tags in git are used to track versions. They are just like versions in realworld scenario.

    creating tag : "git tag -a v1.0"

    push tag : "git push origin v1.0"

merging branches :

    "git merge BRANCH_NAME"   (make sure that you are on the main branch)

rebase :

    "git rebase BRANCH_NAME"

    - difference between rebase and merge : both the commands merges the branches . But the implementation is different.

    - rebase merges the branches on the same path of the main, whereas merge command merges the branch to main coming from other path.

    - Both commands perform same operation but the graph visualization and implemtation is different.

merge conflict :

    - while merging two branches which had changes in the same line of the file, then git throws a merge conflict to the user.

    - user can able to select the lines which he wants to continue with. Thus the conflict can be solved.

time travelling :

    - moving to the existing commits using commit's hash code.

    - "git checkout CODE"

    - this move back does not effect any previous branches and it is independent of them.

    - further changes from here must be made on a new branch.

Git stash :

    - this command is used to save the uncommitted changes.

    - the changes that we are not willing to commit into the commit history can be stashed.

    - so that we can work on other with out effecting this.

    - to get stashed changes back we use "git stash apply".

    - to view stash list "git stash list".

Git fork and pull request :

    - forking is used to take other's repository into our repositories. so that we can make any changes to that repo and creates pull request.

    - the repo owener will get a pull request, so that he can verify the changes and can accept the changes or reject the request.
