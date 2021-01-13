# aws_git
aws_git_project


# Steps for performing git project from AWS EC2 instance 

Login into AWS EC2 instance using terminal 
!
Update yum packager                        - " yum update -y "
!
Install git                                - " yum install git -y "
!
Check if git has been install successfully - " which git "
!
Check the version of git installed         - " git --version "
!
Create git user and email componet for tracking - " git config --global user.name " Pravin Kalake" " & "git config --global user.email " Pravin.kalake@outlook.com "
!
Create a directory/workspace where all code will be written and commited to Central git repo  - " mkdir aws_git_project "
!
Navigate to directory created and perform git initialization -  git init " .....( this creates a hidden .git directory inside current directoy )
!
Create a new file and write a code                           -  nano myfile1 "
!
Check the status of file if its addeded to staging space     -  git status "
!
Add the created/modified file to staging space               -  git add . "
!
Commit the file added to stating space to Local repto        -  git commit -m " my first commint from mumbai instance "
!
Check the commit id and logs                                 -  git log 
!
Check changes made on file                                   -  git show <first-few-char-of-commitid->
!
Add remote repo to this folder to keep ready for push        -  git add remote origin https://github.com/PravinKalake65/aws_git.git
!
Perfom push from Local repo to Git Hub central repo          -  git push remote -u https://github.com/PravinKalake65/aws_git.git
!

