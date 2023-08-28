Git Commands Push
=================

# Git Clone or Push 

## If you create a repository in your GitHub account and use its HTTPS GitHub link, then clone the new folder. Paste your documents there, add a commit, and push to your repository using the following commands.


| Comando | Descripción |
| ------- | ----------- |
| `git clone https://github.com/Mdzeeshan10/Web_app_in_Flask_Python.git` | Your https github url to clone your folder |
| `git status` | Ctatus check |
| `git add .` | You provide . means all files folder in this folder add |
| `git commit -m “My first commit”` | Commit code |
| `git push origine master` | After this command it says your github login credential provide then your code is on github |




## If you already have a folder and you want to add your folder to GitHub, then follow the commands below:

| Comando | Descripción |
| ------- | ----------- |
| `git init` | Inicializa un repositorio local de Git |
| `git status` | Check status |
| `git add .` | All file adds in your git |
| `git commit -m “first commit”` | Commits your code as you want |
| `git remote add origine https://github.com/Mdzeeshan10/Web_app.git` | your https github url |
| `git push -u origine master` | Your all folder puch in your github |




# Large File Transfer to git hub in local to github

| Comando | Descripción |
| ------- | ----------- |
| `git init` | Inicializa un repositorio local de Git |
| `git remote add origin https://github.com/Mdzeeshan10/Web_app.git` | Iyour https github url |
| `git lfs install` | Install in Large file system librrary in their |
| `git lfs track *.h5  *.pkl` | track the large file persent intheir persent all means (*) and format ,means (.pkl) other format as per your data format in case different format not run this command write single format |
| `git status` | Check the Staus |
| `cat .gitattributes` | Check in this '.gitattribtes' folder waht persent to use cat command  |
| `git add .gitattributes *.h5 *.pkl` | Adding files |
| `git commit -m "message"` | Commits your code as you want  |
| `git push origin branch_name` | Your all folder puch in your github |
| `git lfs push origin branch_name` | Above command not work use it |


## Creating new branch and moving one branch to other.

| Comando | Descripción |
| ------- | ----------- |
| `git branch branch_name` | To create new branch |
| `git checkout branch_name` | to go to the new branch |
