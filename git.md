### git commands

* git status
* git init -b main --> will create a empty repo on branch main
* git add fileName
* git add . --> to add all files into staging area
* git log --> to know about the all commits done in this repo
* git commit -m "message" --> to commit the changes made
* git commit -a -m "message" --> to stage and commit files in a single command 
* -a --> to stage the modified files 
* -m --> indicating the message
* after making changes --> have to move the files into staging area --> then only we can commit the made changes.
* git remote -v --> to know which is our origin, we can change that name origin also
* git remote -v --> to know which remote repositories are connected with working directory
* git remote remove origin --> to remove currect remote origin
* git branch -M main --> to change the branch from master to main
* git push -u origin main --> to push the commited files into remote origin
* git tag --> two types: Annotated Tagging, Lightweight Tagging
* git tag -a v1.0 -m "1st release" --> to create a version via tag
* git tag --> to see the all tags
* git show v1.0 --> to know about v1.0 tag
* git checkout **new branch name**--> we can change our branch name 
* git checkout -b feature1 --> to create a new branch (feature1 is new branch name)
* git branch --> to list the availabe branches
* git branch --all --> also list the all available branches
* by indicating *feature1 --> can know feature1 is the **active branch**
* to create a new branch we can use **checkout and switch** , both are same
* git switch main -> to switch from feature1 branch to main branch
* git switch feature1 --> to switch from main branch to feature1 branch
* git checkout -b **new branch name** --> if we are creating a new branch using checkout , have to **-b**
* git switch -c **new branch name** -->  if we are creating a new branch using checkout , have to **-c**
* git branch -d feature2 --> to delete a branch
* if we are in main branch , we can able to view only the files which are created while in main branch
* if we moved to another branch , we cannot able to view tha another branch's files...
