https://www.youtube.com/watch?v=O00FTZDxD0o

Git Bash terminal C:\Program Files\Git\git-bash.exe
pwd  - command to print current directory
~  - current directory of user (here C:\Users\4ohol)
.  - current directory
cd <symbols> + <Tab>  - list of items in the current folder that begin with <symbols>
ls  == dir (UNIX)
ls -la  - show hidden file/folder
mkdir  - create new folder (UNIX)
echo "text" > file-name.txt  - create a text file
cat file-name.txt  - read a text file
rm  - delete file  
<command> --help  - command help

Git
git --help  - help
git init  - initialize Git in the current folder 

git status - info about file changes
git log  - history of commits

git branch  - list of branches
git branch -a  - list of branches (including remote branches)
git branch <new-branch>  - add branch with name <new-branch>
git branch -m <new-name>  - rename branch 
git branch -d <branch>  - delete branch 

git add .  - prepare all changes to commit 
git add <file>  - prepare <file> to commit 

git commit -m "message"  - commit changes with title "message"

git checkout <commit-hash>  - upload files from repository into work folder
git checkout <branch>  - upload files from repository into work folder

git cat-file -t <hash>  - read type of items
git cat-file -p <hash>  - read text of items

git merge <branch>  - merge branches
git merge -m "message" <branch>  - merge branches with message

git clone <url>  - clone remote repository into local
git remote add origin <url>  - connect to remote repository
git pull  - pull from remote repository
git push  - push into remote repository
git push -u origin <branch>  - upload changes from local branch into remote with establishing a connection between them

git remote -v  - list of connections with remote repository
git branch -vv  - shows the corresponding branch in the remote repository
 

