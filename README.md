Used to practice git.

configuration : "git config --global user.name USER_NAME"
"git config --global user.email USER_NAME"

adding file to staging area : "git add filename".

adding file to commit history : '''git commit -m "commit message"'''

connecting remote repository : "git remote add origin REPO_URL"

pushing into the remote repo : "git push origin BRANCH_NAME"

to look difference b/w edited and already commited : "git diff"

if the edits are staged : "git diff staged"

creating new branch : "git checkout -b BRANCH_NAME"

creating branch using switch : "git switch -c BRANCH_NAME"

deleting a branch : "git branch -b BRANCH_NAME"

tags :

    tags in git are used to track versions. They are just like versions in realworld scenario.

    creating tag : "git tag -a v1.0"

    push tag : "git push origin v1.0"

merging branches :

    git merge BRANCH_NAME   (make sure that you are on the main branch)

rebase :

    git rebase BRANCH_NAME

    - difference between rebase and merge : both the commands merges the branches . But the implementation is different.

    - rebase merges the branches on the same path of the main, whereas merge command merges the branch to main coming from other path.

    - Both commands perform same operation but the graph visualization and implemtation is different.
