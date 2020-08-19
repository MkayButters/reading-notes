# Git information
## https://blog.udemy.com/git-tutorial-a-comprehensive-guide/

- A ___CVS___ is basically a hard drive
- A ___DVCS___ is a mirrored repository that multiple clients edit and has more security against file loss in the event the CVS is corrupted 
- Git is a __DVCS__ and as a gatekeeper for your repositories makes it very difficult to lose data.

 ```Git resides in main states: committed, modified and staged```
- After you edit a file, Git flags it as modified because of changes made after the previous commit.
- You stage the modified file then, you commit staged changes.
- Git allows multiple people to work on one repository, from their local device through branching. 
- By pushing new information into the git server and pull all information out you can stay up to date on the Git file localy and on the master GIT
- Git is able to remove and correct mistakes from a file
- Creating tags are as easy as git tag  _version you want_
***
### __DONT FORGET__:   (A)dd (C)ommit (P)ush

 git add .  (adds all files that have been changed)

 git commit -m "made changes to text files"

 git push https://github.com/MkayButters/reading-notes.git master



[<=BACK](README.md)