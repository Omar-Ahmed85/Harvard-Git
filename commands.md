/* < > indicate what should be written, () indicate the job of the command line */

git clone <url of the repository> (To copy a repo to your device)

ls (To show all the files and sub-folders inside the current directory)

touch <The name of the file> (To create a new file, also you can just use a text editor)

git add <file name> (To track the file)

git add . (To track all the files within the directory)

git commit -m "<Any message>" (To commit changes to the repo)

git status (To tell us some info about the repo)

git push (To push your changes to the online repo at github.com)

git commit -am "<message>" (To combine between the git add, and commit changes to all files)

git pull (To pull the latest version of the online repo to my local one)

git log (To see when a particular line is changed and who made that change)

/* git reset */ (To go back to another version of the repo)
git reset --hard <The commit hash you can get the hash from the git log command line>
git reset --hard origin/<branch name>

git branch (To tell us the branch that we are currently using)

git checkout -b <branch name> (To make a new branch and switch to it)

git checkout <branch name> (To switch to another existing branch only)

git merge <branch name> (To merge two branches)