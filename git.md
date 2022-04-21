## git Commands

#### **branch related** 
```
git branch -a                                       # List all branches
git branch                                          # List currently active branches
git checkout <branchname>                           # check out existing branch
git checkout -b <branchname>                        # create new branch
git branch -D <branchname>                          # delete a branch
git diff <branch1> <branch2>                        # diff between branches
git branch --set-upstream-to=origin/5.0 5.0-final   # git set branch upstream
```

#### **code change related**
```
git diff                                             # show uncommited changes
git diff --cached                                    # show added changes
git show --pretty="" --name-only <commitid>          # show files that are modified in given commit
git show [<commitid>]                                # show changes in the latest commit or specified commit
git branch --contains <commitid>                     # List branches that contains this commit id
```


#### **stash related**
```
git stash                             # stash current changes
git stash -list                       # list all stashes
git stash pop                         # applies top most stash and deletes it
git stash apply                       # applies top most stash but does not delete
git stash drop                        # drop top most stash
git stash show -p stash@{0/1/2/3}     # show code changes with stash id
```


#### **cherry-pick**

```
```

#### **reset changes**
```
git reset --hard HEAD^                # Undo latest commit
git reset --soft HEAD~1               # Undo latest commit without losing changes
```

#### 
