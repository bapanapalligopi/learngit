## waht is git stash?
# if there is file that is already tracked by git in any branch and if you do any actions on that file
and you wanna move to different branch then git won't allow you to checkout another branch  unless
you do
1. git commit
2. git stash =>temporerily stash the changes with out commit
3. git stash list => list all stashes
4. git checkout another
5. do some
6. git checkout master
7. git stash apply stashId
8. 
