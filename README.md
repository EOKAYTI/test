1. Create and checkout branch

git checkout -b <branch_name>

2. Delete branch
   . Local: git branch -d <branch_name>

. Remote: git push -d origin <branch_name> 3. Add file to staging area

. File: git add <file_name>
. All: git add

4. Commit staged file

git commit -m "<message>"

5. Push commit to remote branch

. First: git push -u origin <branch_name>
git push

6. Merge branch

git merge origin <branch_name>

7. Revert local commit

git revert <commit id>

8. Pull commit from remote branch

git pull origin <branch_name>
