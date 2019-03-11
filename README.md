# github-commands
Creating this because I have amnesia and don't want to google everytime 

# Commands Related to Branches
`git checkout branch_name`  // switch branch \n
`git checkout -b new-branch-name`   // make new branch 
`git branch` // check out which branch 

# Commands Related to Making a PR
`git status` // documents you changed appear red
`git add -u` // adds the updates
`git commit -m "your_message"` // keep commits granular
`git push`


# Rebasing to Master
`git checkout master`
`git pull origin master`
`git checkout existing-branch-name`
`git rebase master`
`git push origin <branch_name> --force`  // need to force-push
