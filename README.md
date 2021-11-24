## Steps for uploading files on github using terminal:

git install


git --help


pwd

ls -latr

git init

ls -latr

gedit .gitignore  (/filename/ write in the fiel)

git add .

git status

##set global settings:##

git config --global user.name "...."

git config --global user.email "...."

git commit -m "message"

git status 

git remote add origin [url copied]

git push origin master



##upload changes to the github##

git push origin branch_name



## According to the github documentation

### …or create a new repository on the command line

echo "# Web-Development-Project" >> README.md 
git init  
git add README.md  
git commit -m "first commit"  
git branch -M main  
git remote add origin https://github.com/PriyankaJhamb/Web-Development-Project.git  
git push -u origin main  

### …or push an existing repository from the command line

git remote add origin https://github.com/Username/repositoryname.git   
git branch -M main  
git push -u origin main  

### …or import code from another repository4454f70891ad2d363025e26f691733c010d1b1a8
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.  

## Clone repository 

```git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY```

[Reference Link](https://www.earthdatascience.org/workshops/intro-version-control-git/basic-git-commands/#:~:text=From%20your%20repository%20page%20on,like%20to%20clone%20your%20repository.)

## Delete some commits from github

```git reset --hard <last_working_commit_id>```


```git push --force```

[Reference Link](https://stackoverflow.com/questions/3293531/how-to-permanently-remove-few-commits-from-remote-branch)

## fetch all changes from remote to local

```git fetch --all ``


git pull origin main
git push orign branchname
git branch - Checking the no. of branches, ur current branch
git checkout branchName
git checkout -b branchName//creating the branch and switching the branch
