##  how to remove the branches locally and remotely
  - locally : we can use this command -d to remove merged branch, and we can use -D to enforce removing a non-merged branch.
  ```
  git branch -d <branch-name>

  ```
  - remotely : we can use this command 
  ```
  git push origin --delete <branch-name>

  ```