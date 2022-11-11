# wth are these ? it must be stopped
## branch
- is a pointer to one specific commit
- doesn't have to diverge from a graph
- it only diverges if a commit is made on a common ancestor commit
- two commits might be on different branch
- to delete a branch, we must checkout other branch 
- if we click delete both local/br and origin/br, only the origin will be delete, but the local will still stay (if we're still on br)
- be **VERY CAREFUL WHEN RESETING LOCAL BRANCH TO REMOTE BRANCH, YOUR WORK MIGHT BE LOSS**

# git pull
- git pull = git fetch then git merge
- git fetch means download all the files from the remote to local
- dont let the graph representation mislead you, the local tag icon commit node might be higher than the one of the remote node, but still you could be both behind and ahead. You must see the common ancestor commit node

-dafuq is fast-forward


# refs ? refspecs ?

# git rebase
# fork
# pull request
# stashing
# pop
# git pull remote branch ??
# git cherry pick ?
# git merge ?

# why the fuck would they say **Create a new branch for this commit and start a pull request.**
