
# Git Practical

# Steps Performed

- Created a GitHub repository with a README file and cloned it to the local system.

- Created a develop branch and pushed it to GitHub.

- From develop, created two feature branches: test1 and test2

# COMMIT-MSG Hook

- Created commit-msg hook that checks that empty commit message is not valid.

# Work in test1 branch

- In test1 branch  created index.html and made few commits in it and pushed it.

- Created the PR request from test1 branch -> develop branch to get all commits done in test1 branch to develop branch 

- Pull the develop branch locally in the system.

# Work in test2 branch

- Switched to test2 branch and made few commits in index.html and pushed those commits in github.

- Now for getting all latest update made in develop to test2 branch I do rebase in test2 branch.

- Because of this conflicts were there and conflicts were solved and rebase was done and test2 branch now has all latest updates including develop branch and pushed it to github.

- Created PR from test2 -> develop so develop has all commits including test2 and pulled the develop branch locally in the system.

# Tagging

- Created the tag of latest commit of develop and pushed tag to github.

# Work in test3 and test4 branch

- Created test3 branch and test4 branch from develop.

- Made a commit in readme file and pushed it and made a commit in index.

- In test4 branch cherry pick the commit made in test3 branch.

- Changed the commit message using amend.

- Added few commits in test4 and deleted last commit of test4 branch using git reset.




