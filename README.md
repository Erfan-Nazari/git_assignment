# Git Assignment - Erfan-Nazari


a. What is an issue?
It is a feature on Github that allows us to track requested changes and features in software project. The issues are related to the repository and not branches.

b. What is a pull request?
The pull request on Github is a proposal to merge a set of changes from one branch into another branch. The pull request can be reviewed by collaborators before it is accepted and merging is done.

c. Describe the steps to open a pull request?
1) Go into the corresponding repository.
2) Click on the "Pull requests" tab on top.
3) Click on the green "New pull request" button on top right.
4) From drop-down menu choose that you want to create a pull request from which branch to which branch.
5) Review the changes.
6) Click on the green "Create pull request" button on top right.
7) Add a title and a description for the pull request.
8) Click on the green "Create pull request" button.

d. Describe the steps to add a collaborator to a repository (share write permissions)
1) Go into the corresponding repository.
2) Click on the "Settings" tab on top.
3) Click on the "Collaborator" on the right.
4) Click on the green "Add people" button.
5) Search and select the collaborator account.
6) Click on the green "Add ... to this repository" button.

e. What is the difference between git and GitHub?
Git is a version control software/application that developers install locally on their computers.
Github is an online service built to run Git in the cloud.

f. What does git diff do?
The command "git diff branch1 branch2" shows the changes between branch1 and branch2.

g. What is the main branch?
The main branch is the official working version of the project. To make sure that the main branch always works properly, we usually don't apply changes directly to the main branch. We create new branches and apply the changes or updates to that branch. Then, we create a pull request to merge that branch to the main branch when it is ready. After reviewing and making sure that the changes work properly, we accept the pull request and merge the updated branch to the main branch.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, as I explained above: To make sure that the main branch always works properly, we usually don't apply changes directly to the main branch. We create new branches and apply the changes or updates to that branch. Then, we create a pull request to merge that branch to the main branch when it is ready. After reviewing and making sure that the changes work properly, we accept the pull request and merge the updated branch to the main branch.