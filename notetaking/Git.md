is used for repository management where you can remotely append/edit the content.

we initialilze the repo with 

git init

we add the files to be tracked with 
git add

we commit the repository with 

git commit

we push the commit to the remote repository with 

git push


|   |   |   |
|---|---|---|
|`git init`|Initializes a Git repository|Creates `.git/` directory|

|   |   |   |
|---|---|---|
|`git add <file>`|Adds files to staging|Moves files to **staging area**|

|   |   |   |
|---|---|---|
|`git commit -m "message"`|Saves changes permanently|Creates a new **commit**|

|   |   |   |
|---|---|---|
|`git push origin main`|Uploads commits to remote|Updates the **remote repository**|