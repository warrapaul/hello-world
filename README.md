# GIT BASICS

#1. CREATING DJANGO PROJECT
- open folder
- django-admin startproject djangoRestAPI
- cd .\djangoRestAPI\
- pythom manage.py startapp methodBased
**************************************************************************************

#2. ADD EXIXTING PROJECT TO A GIT REPO
- create a new repo
- on the project initialize git -> git init
- add all untracked files -> git add .
- git commit -m "first commit"
- add the repo, providing branch name and remote url ->git remote add origin https://github.com/warrapaul/djangoRestAPI.git
- create branch -> git branch -M main
- push content to the remote url using upstream for the first push ->git push -u origin main
*************************************************************************************

#3. ADDING .gitignore file
- in the base directory of the project, create .gitignore file and paste content from https://github.com/github/gitignore/blob/main/Python.gitignore
