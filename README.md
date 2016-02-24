# GitCommandTest
This repository is for testing Git Commands.

This branch is created for editing already pushed messages.
1.git rebase -i <hash-of-commit-preceding-the-incorrect-one>
2.In the editor that opens, change pick to reword on the line for the incorrect commit.
3.Save the file and close the editor.
4.The editor will open again with the incorrect commit message. Fix it.
5.Save the file and close the editor.
6.git push --force to update GitHub.
