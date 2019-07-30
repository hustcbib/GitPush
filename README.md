# GitPush


## Push to github 

### 1、Github  using   

- establish a repository in the github
- git clone https://github.com/quronghui/test2.git ( Github already have reposity )
  - Change or add files in the floder    
- git add -A (or git add . )   
- git commit -m "hello"     // "里面的是注释消息"
- git push -u origin master 

### 2、When we have a project in local ,  github's repository is blank.

- git init  
- git add -A ( or git add . )   
- git commit ( or  git commit -m "hello" )  
  - ( git commit -- use vim cmd  )  
- git remote add origin https://github.com/quronghui/test2.git
- git push -u origin master  

#### Notes

- "git status" , See files status   
- "git log" check push track    
- "git diff" check change part  



## If you have other origin master, you can do this to release it

- git remote -v   （ we can check this term's origin ） 
- git remote rm origin 

## Fetch to master

- git fetch

- git merge

  ### Notes

- Don't use git pull

## Git Branch

- Build a branch , divide the work  

- git branch hello ( "hello" is branch name )   
- git checkout hello ( Enter branch )  
  - you can push you code in your branch hello    
- git checkout master  ( Cut directory )    
- git merge hello ( Combine branch directory to master directory )   

## Git Relase

- We can do work about version management,  backup file  

