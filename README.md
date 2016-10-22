# GitHub Tutorial

by **Mena Bebawy**

---
## Git vs. GitHub

##### What is git?
Git is _version control software_ that helps you save your work. It allows you to save your changes as you progress and you can refer back to any version of your work whenever you want. Unlike Github, git runs locally. Meaning that the work you do on git is only saved on your device. Git also does not need Github to run in order to work.
##### What is github?
Github is where you save your repository. Unlike git, github requires git in order to run. Github also runs in the cloud where you can save all your changes without having to worry about losing them. You can use github to work with others on the same project simultaneously without affcting eachother's work. You can also see your changes in order and return your project to an older version if you decide to do so.

---
## Initial Setup
In order to setup your github account follow this tutorial:  

1. The first thing that your going to need to do is sign up for github by going to [this site](github.com). Sign up and get started with github. 
2. The second thing you need to do once your signed up is create a git repository using git by typing the command `git init` and naming it. **Do not** do anything in github yet.
3. You will then need to go to github and create a repository by going to the top right corner and pressing on the + and then clicking on "new repository".
4. You then name your repository and decide if you want it to be private or public. **Remember: your repository name has to be the same as your directory's name.**
5. Press on create new repository, then you will see in the top left corner SSH or HTTTPS; choose the SSH option. 
6. Then Scroll down untill you see this:  
![screenshot](git remote.PNG)
7. Copy the first line and paste it into your command line. This should clone your file.
>git remote add origin git@github.com:<username>/trial.git
8. Copy the second line and paste it as well. Once this is done you should refresh your github and see your new changes.
>git push -u origin master
9. _You are now done!!_

---
## Repository Setup

1. In your command line make sure you are in the directory where you want to create your repository.
2. Type in `git init` in order to make a new repository.
You will then need to go to github and create a repository by going to the top right corner and pressing on the + and then clicking on "new repository".
4. You then name your repository and decide if you want it to be private or public. **Remember: your repository name has to be the same as your directory's name.**
5. Press on create new repository, then you will see in the top left corner SSH or HTTTPS; choose the SSH option. 
6. Then Scroll down untill you see this:  
![screenshot](git remote.PNG)
7. Copy the first line: `git remote add origin git@github.com:<username>/trial.git` and paste it into your command line. This should clone your file.
8. Add your files to the staging area by typing in `git add --all`. This will add all your files including the deleted ones.
9. You will then need to commit your files by typing in `git commit -m "message name"`. Make sure that your message is appropriate; it should tell you what changes you did and be in the present tense. _EX: "fix screenshot"_
8. Copy the second line: `git push -u origin master` and paste it as well. Once this is done you should refresh your github and see your new changes.


---
## Workflow & Commands