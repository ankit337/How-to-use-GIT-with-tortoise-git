# How-to-use-GIT-with-tortoise-git
---
If your team working directly on master branch then follow below steps
---

:sparkles: For Taking latest code from server
-	`GIT Sync` (It will open GIT sync UI)
 -	`Stash Save` (it will save your changes to some temp folder)
 - `Pull` (It will get latest code into your repo)
 -	`Stash Pop` (It will bring your changes back to your repo from the temp folder)
 
    > While doing Stash Pop there may be conflict(:boom:) on some files which is committed by other users, that you need to resolve

 -	Now you can start working on latest code


---



:sparkles: For Commit something
 -	`GIT Sync` (It will open GIT sync UI)
  - `Stash Save` (it will save your changes to some temp folder)
  -	`Pull` (It will get latest code into your repo)
  -	`Stash Pop` (It will bring your changes back to your repo from the temp folder)
    
    > While doing Stash Pop there may be conflict(:boom:) on some files which is committed by other users, that you need to resolve
  -	`Commit` (It will Open the git commit UI, Select only those files that you want to commit and then do commit)
  -	`Push` (It will push your commit to the server)  (If you are getting  any error(:boom:) like '*git did not exit cleanly…*' then, in that case do `Fetch & Rebase` )
