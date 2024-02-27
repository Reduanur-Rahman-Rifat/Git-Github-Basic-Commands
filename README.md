# Git-Github-Basic-Commands
{
untracked - new files that git doesnot yet track
modified - changed
staged - file is ready to be commited
unmodified - unchanged
}

check git version :git --version
check working directory: pwk
check list file: ls
check hidden file:ls -a (all file)
for go to next directory : cd (change directory)
clear terminal: clear

set up:
//...................................//
git config --global user.name "Reduanur-Rahman-Rahman"
git config --global user.email "reduanur1225@gmail.com"
git config --list


clone & status
clone-clonning a repository on our local machine
status-diaplays the state of the code
//...................................//
git clone link
git status


Add and commit
add-adds new or changed files in your working directory to the Git area
commit it is the record of change
//...................................//
git add file name.extention
git add .     (for add all files)
fit commit -m "some message"


push command
push - upload local repo content to remote repoo
//..................................//
git push origin main
