It is the responsibility of developer to check in immediately after the development.

Following are the guidelines developer should follow while checkin the code to dev branch.

1. Create a branch from the dev branch and make sure to name the branch with dev_.
2. Clone the new branch created to local directory.
3. Copy the code from python code directory to backup directory before making any changes to the python code directory.
4. For existing code you can replace the code with newly file.
5. Existing file with new changes should have a proper change log with details including developer who changed the code along with the date changed and add comments if necessary 
5. Once the changes are done make sure to review the changes using git GUI .
6. Once reviewed all the changes need to staged.
7. Staged changes can be committed.
8. Before committing provide a commit message.
9. Once committed review the status which clearly indicates how many commits are main branch ahead. Review it.
10. Once everything is fine push the code to git hub.
11. Review the code and create pull request.
12. Code should at least be reviewed by another developer before approving the pull requests.
13. Once the pull request is approved merge the changes.
Once the code in dev branch is reviewed create a pull request to test branch

Once tested the code can be promoted to production.
