# Git Essential Commands For Developers

# Delete a file and directory
#### rm & del = is to delete files
#### rm -r & rmdir = is to remove directories


# copy files
#### cp filename directory name


# rename file
#### mv oldfile_name newfile_name  = within the directory,it will rename the file
#### mv oldfilename directory_name/newfile_name = delete the existing file and create new file



# to go back to parent directory
#### cd ..

# to go to home directory
#### cd 

# to go two steps back
#### cd ../../



# to make directory
#### mkdir directory_name


# to create a file
#### Touch filename.txt

# vim editor
#### vi filename.txt


# nano editor
#### nano file.txt


# pwd - print working directory
#### pwd


# change directory
#### cd directory_name

# packages
#### installation of packages ,only in linux


# list directories
#### ls = list all files
#### ll
#### ls -a = open hidden files
#### dir = in windows


# to read files
#### cat filename

# to list all the head files
#### head filename

# to list all the bottom files
#### tail filename

# to check the configurations
#### git config --global user.name
#### git config --global user.mail


# to set the configurations

#### git config --global user.name "Meghanath"
#### git config --global user.mail "Meghanathabc@.gmail.com"


## <-----Git Commands-------->
#### git init = to initialise a empty git repository
#### git add = to add files to staging area
#### git commit -m "proper message" =to create new commits with staging area
#### git push = to upload local commits to remote repo
#### git status = to check the status of repo

#### git add = to move the files into staging area
#### git reset = to reset the staging
#### git log = to see the history of git operations

#### git diff file_name = to see what changes i have done in the file,before adding to staging area(tells which part of file is changed)
#### git status = which file has been changed or modifed

#### gitignore = ignore modules,env file,temp files from being tracked

#### git branch -a =to see all the branches
#### git branch branch_name = create new branch branch_name
#### git switch branch_name = switching to another parallel universe 

#### git checkout -b branch_name = to switch and as well as create new branch
#### git remote add origin url

#### git push origin branch_name

#### git pull origin branch_name
#### git clone url

#### git branch -D branch_name = to delete a branch permanently on cli
#### git push origin --delete branch_name = to delete a branch on remote


# cloning and forking
#### git clone url
#### fork = is done on github only



# commit history locally and on github



# removing and moving assets
#### git mv oldfile_name newfile_name = doing git mv ,will tell the file has been moved or renamed
#### mv oldfilename newfilename = we should add externally to staging area
#### (note : so better to use git mv)


# branches are a fundamental part of git
#### git merge newbranch = merges the  changes done in newbranch into current branch

# setup github pages
npm install gh-pages --save-dev




# markdown (Readme.md)
#### headings : there are six levels of headings.use # in front,increase the no.of #,to decrease the font size





## shortcuts:
#### ctrl+c = to cut &
#### ctrl +l = to clear all the history at once

## ITALICS:
* = make italics
## BOLD:
** = make bold
## LINK:

[click here](https://github.com)














