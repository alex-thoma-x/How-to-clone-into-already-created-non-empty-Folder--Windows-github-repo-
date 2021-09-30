# How-to-clone-into-already-created-non-empty-Folder--Windows-github-repo-
How to clone into an already existing folder which is non empty in wondows using Git Bash

1) First go to the Folder to which it needs to be cloned  

2) Open Git Bash in the Folder
  
3) Start a new git repository  using this command in the Git Bash
```$ git init```  

4)Now add the remote from where you want to clone
```$ git remote add origin https|<the repo path>```
  
5) Add the files  
```$ git add .``` for addding all files and 
```git add filename.extemsion``` for individual files

6)Commit the Files
```git commit -m'my first commit'```  
  
7)for push
 ```git push -u origin master```
  
8) To pull and merge with local git  
```$ git pull origin master```  
resolve the merge conflicts if any
  
