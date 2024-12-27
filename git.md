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
