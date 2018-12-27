# testGit
This is for  testing  purpose.
### How to work 
#1st step:
install git in your system.
#2nd step
Open git Bash
#3rd step
type: cd /directory name(C,D,E,F any thing which you want)
#4rt check available file and folder
ls
#create directory where you want to clone git reposetory
mkdir (directory name)
#Go innside the directory.
git cd (directory name)/
#Configure Github
git config --global user.name "user name"
git config --globla user.email "email id"
## clone reposetory
#copy https link of that reposetory from github
git clone (paste that link here)
# go inside git folder
cd (git folder name)/
###Upload file in github
# add the file
git add (file name with extension)
#check status
git status
## first commit then transer your file in github
#commit
git commit -m "commit massage" (file name with extension)
# then transfer you file
git push -u origin master

### change in your file and then update in github
#first update in your file then check  status it was updated or not 
git status
#commit
git commit -m "commit massage" (file name with  extension)
#push
git push -u origin master



