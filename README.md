1. New feature branch out of master 
`git checkout -b new_feature`
2. Commit your work
3. Rebase over master (remember to git fetch/git pull before)
`git rebase -i master`
4. Resolve conflicts and squash your work
5. Push to origin
`git push origin new_feature --force`
Open a pull request or merge
