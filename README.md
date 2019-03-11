# github-commands
Creating this because I have amnesia and don't want to google everytime <br />

# Commands Related to Branches
`git checkout branch_name`  // switch branch <br />
`git checkout -b new-branch-name`   // make new branch <br />
`git branch` // check out which branch <br />

# Commands Related to Making a PR
`git status` // documents you changed appear red <br />
`git add -u` // adds the updates <br />
`git add .` or `git add --all` // add all files
`git commit -m "your_message"` // keep commits granular <br />
`git push` <br />


# Rebasing to Master
`git checkout master` <br />
`git pull origin master` <br />
`git checkout existing-branch-name` <br />
`git rebase master` <br />
`git push origin <branch_name> --force`  // need to force-push <br />
