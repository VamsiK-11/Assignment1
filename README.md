# Assignment1
DevOps Tools Internals Assignment
First i created a folder named git in my local system and i initialised

cd E:\Git

git init

git global config --user.name"VamsiK-11"

git global config --user.email"vamsikana1@gmail.com"

git remote add origin https://github.com/VamsiK-11/Assignment1.git

notepad sample.txt    #I added a text saying "Hey This is Vamsi from 5CDV-1" in master branch

git add .

git commit -m "My First Commit"

git push origin master

git branch feature

git checkout feature

notepad sample.txt      #To the same file i edited the text to
"#In the master branch
Hey This is Vamsi from 5CDV-1

#In the feature branch
Name : K Vamsi Krishna
Roll No : 20211CDV0030"

git add .

git commit -m "My Second Commit"

git push origin feature

git checkout master

git merge feature branch        #here i had a merge-conflict so i pulled the repository and did changed   

git push origin master
