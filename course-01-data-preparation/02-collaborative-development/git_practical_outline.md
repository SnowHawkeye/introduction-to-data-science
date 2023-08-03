# GitHub practical

1. Create a git project
	- Create a new project online
	- Clone project locally
	- Add .gitignore and README (show the use of gitignore)
	- Define and document code conventions and git flow
	- Create main and develop branches
	- Add collaborators (let everyone install git and create an account)

2. Define everyone's tasks
	- Separate the team into subgroups
	- Add mock issues and assign them to the right people
	- Let everyone download the project and checkout the dev branch
	- Check branch history

3. Work on "features"
	- Let everyone create their feature branches
	- Show how to rename a branch
	- Create files and show how to reset / delete
	- The mantra: status - add - commit - push (and choosing committed files)

4. Creating a pull request
	- Let everyone create a pull request for their work in their sub-group
	- Let everyone comment / validate other people's pull requests
	- Do not merge yet

5. Manipulating your commit history (updating the PR)
	- git commit --amend --no-edit
	- git rebase -i HEAD~2
	- pick / reword / fixup
	- Updating the PR
	- Merge the PR (within groups, not within dev yet)

6. Managing conflicts
	- Within each group, intentionally create conflicts
	- Solve conflicts manually or with PyCharm

7. Other functions
	- git stash / git stash pop
	- git cherry-pick

8. Merge everything into develop