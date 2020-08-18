
a cvs is basically a hard drive
a DVCS is a mirrored repository that multiple clients edit and has more security against file loss in the event the CVS is corrupted 
Git is a DVCS and as a gatekeeper for your repositories makes it very difficult to lose data. Git resides in main states: committed, modified and staged
After you edit a file, Git flags it as modified because of changes made after the previous commit.
You stage the modified file.
Then, you commit staged changes.
