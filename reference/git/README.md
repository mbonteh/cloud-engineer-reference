Module 0:  Git, Github and Version Control

Working Directory <-add-> Staggging Area <-commit-> Local (Git) Repository <-push-> Remote (GitHub/CodeCommit) Repository


Local Reposotory

git init      // create a .git file in local/working directory and versioning begin.
git add/rm    // add or remove file or folder or all(.) in folder   
git log       // show commit log/history
git status   //
git diff chapter.txt  //
git checkout chapter1.txt // rollback change fome Repository to Working Directory


Remote Repository 

git remote add origin <url>   // by default remote name is origin
git push -u <remote name> <branch name>  / 
    git push -u origin main
    git push -u origin dev
    git push -u origin feature-account_access
git merge
git clone vs fork

get merge

git rebase

git branch  <dev, feature-account_access feature-cicd_pipeline>

pull Request



branch: main, dev, feauture, hotfix, bug 




