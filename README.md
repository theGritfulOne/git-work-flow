# git-work-flow

These are some of the basic github commands:

a. git remote add origin https://github.com/GritfulOne/git-work-flow.git //links local repository to github
b. git push -u origin master //syncs master branch to github 

1. git init //initializes a git project
2. git status //shows current status of project
3. git add "filename" //stages edited "filename" for commit
4. git commit -m "message" //commits changes to branch and adds "message" as commit description
5. git commit -am "message" //stages and commits changes directly
6. git branch develop //creates a branch named 'develop'
7. git checkout develop //switches to 'develop' branch
8. git branch //lists all branches in the repository
9. git checkout -b develop //creates a branch named 'develop' and switches to that branch
10. git flow init //initialized structured git flow

Hopefully this still uploads

The next lines are added using flow feature
11. git flow feature start "feature name" //creates a new feature in the flow and switches to it
12. git flow feature finish "feature name" //merges feature to develop and deletes feature