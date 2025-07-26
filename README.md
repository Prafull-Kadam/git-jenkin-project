# Day 1
### git-jenkin-project
Dev ops training GIT - Jenkin project demo

- Initialize the Git repository using the following command:
- `git init`

- Push the changes in the local repository to GitHub
Open the Terminal and add a remote repository using the following command:
- `git remote add origin <URL>`

- Push the changes to the remote repository using the following command:
- `git push -u origin master`

- Run the following command to check the status of the local repository:
- `git status`
----------------------------------------------------------------
# Day 2
Merging Branches in Git

Go to your repo on main branch
`git pull origin main`

- Create and switch to the new branch
 `git checkout -b dev-v2`

- Add new file/update Readme
- `git add .`

- `git commit -m "day 2"`

- `git checkout main`

- `git merge dev-v2`

- `git push origin main`




