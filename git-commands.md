# github-commands
Creating this because I have amnesia and don't want to google everytime <br />


# Creating Projects
`git init`	Initialize a local Git repository <br />
`git clone ssh://git@github.com/[username]/[repository_name].git`	Create a local copy of a remote repository <br />

# Commands Related to Branches
`git checkout branch_name`  // switch branch <br />
`git checkout -b new-branch-name`   // make new branch <br />
`git branch` // check out which branch <br />

# Commands Related to Making a PR
`git status` // documents you changed appear red <br />
`git add -u` // adds the updates <br />
`git add .` or `git add --all` // add all files  <br />
`git reset` // un-add the file <br />
`git commit -m "your_message"` // keep commits granular <br />
`git push` <br />
`git rm -r [file-name.txt]` // discard files <br />


# Rebasing to Master
`git checkout master` <br />
`git pull origin master` <br />
`git checkout existing-branch-name` <br />
`git rebase master` <br />
`git push origin <branch_name> --force` or `git push origin +reposity_name`// need to force-push after rebasing for changes to be pushed <br />


# Show History/Logs 
`git show --stat sha` <br />
`git log --stat -- path_to_file` <br />
`git log` <br />
`git log --summary`	// View changes (detailed) <br />
`git diff [source_branch] [target_branch]` // shows difference between target & source branch

