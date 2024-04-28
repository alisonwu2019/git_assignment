# Git Assignment - alisonwu2019

a. What is an issue?
An issue in Git is a feature used for tracking bugs, tasks, or enhancements within a project.

b. What is a pull request?
A pull request in Git is a proposed set of changes submitted by contributors for review to merge into the main codebase of a repository, facilitating collaboration and code review among team members.

c. How do I open up a pull request?
Click on Pull Request beside <> Code and click New Pull Request to open a pull request. Select the branch that is going to be merged from and to and click Create Pull Request.

d. Give me a step by step guide on how to add someone to your repository.
1. Navigate to Repository Settings on GitHub
2. Select Manage access under Options
3. Then select  "Invite a collaborator" and type the GitHub username/ email address that you want to add
4. Choose the correct access level for the new user
5. Click Add to send the invitation
6. After the user accepts the invitation, the user will have specified access to the repo

e. What is the difference between git and GitHub?
Git is a version control system that allows users to make changes to the code locally, while GitHub is a platform that hosts Git repositories and provides collaboration features for teams to work on code together over the internet.

f. What does git diff do?
 git diff displays the differences between changes made to files in the working directory and the staging area. This allows users to view the changes before commiting.

g. What is the main branch?
The main branch, also calledd "master", is the default branch in a Git repository where it contains the latest changes and shold have the most stable versions of a project.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, it's generally recommended to create a separate branch (feature/ hotfix) for the changes, make commits there, and then open a pull request to propose merging those changes into the main/ master branch, facilitating code review and maintaining a clean history.