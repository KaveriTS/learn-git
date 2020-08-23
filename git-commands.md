# GIT

## Create a Repository in Git

* Give Any name, doesn't matter the name of the folder or the name of the repository
* Repository just means folder. Just another name for folder
* Select Either Public or Private
  1. Private Means No One Can Access Except You
  2. Public means anyone can access over the web

## Initialise a Git Repository

* Initialize a git repository to keep track of the folder
* Make sure that the path is correct (/Desktop/study-git in this case)
  
### Initialises git repository

` git init ` 

Output : 'Initialized empty Git repository in /home/kaveri/Desktop/study-git/.git/'

### Add Changes

`git add .`

You have to add the changes so that everychange you add gets ready to be committed.

### Now add a commit message

Commit the changes with a message that you understand so that you can understand was it was later
This is going to your first commit, basically it suggests commitmenet!

` git commit -m "My First Commit in Github" `

output: [master (root-commit) 8c57766] My First Commit in Github
 1 file changed, 35 insertions(+)
 create mode 100644 git-commands.md

35 insertions basically means words, and we have one fille in this folder, which is this file git commands.md

### Add the origin

` git remote add origin https://github.com/Kaveriiii/learn-git.git`

Your folder doesn't know where our repository exist, so add this link. YOu have to only do this the first time you make a repository.ok

### Now push to github


` git push origin master `

Basically you're pushing the committed changes to github
I'll explain master later

### Check Git status

` git status `

Since you made changes, you have to add and commit, then push again to make it upto date. You can do whenever you want. Save before adding. Else it won't be added

