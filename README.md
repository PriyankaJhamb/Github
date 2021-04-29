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

### …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.  
