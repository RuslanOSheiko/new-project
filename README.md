1. Create a new "new project" directory
```
mkdir new-project
```
2. Go into "new project" directory
```
cd new-project
```
3. Initialize the new Git repository
```
git init
```
4. Create a new "README.md" file and add the opening text to it
```
nano README.md
```
5. Stage README.md to prepare for commit 
```
git add README.md
```
6. Commit changes with the commit message “init”
```
git commit -m "init"
```
7. Create a new "development" branch and switch to it.
```
git switch -c development
```
8. Add the instructions to the "README.md" file and stage file to prepare for commit
```
nano README.md
```
```
git add .
```
9. Commit changes to the "development" branch with a commit message
```
git commit -m "Add instructions to the README.md file"
```
10. Merge changes from the "development" branch into the "main
```
git switch main
```
```
git merge development
```
11. Check the status of the repository
```
git status
```