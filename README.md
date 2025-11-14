# cloudcomputingnotes
cloud computing notes<br>
# Git commands<br>
git clone gitlink(to clone a repo on local pc)
git push (for pushing any file to a repo)<br>
git add (to add any file to staging)<br>
git push origin main<br>
git revert (to revert a commit)<br>
git fetch (to upate repo with the repo on the remote)<br>
git fetch origin<br>
git branch -r(for checking the remote branchs)<br>
git branch -a(for checking all branches)<br>
git status (for checking the status of a branch if any file is added changed or deleted etc)<br>
git checkout branchname (used to navigate to branches)<br>
git branch newbranch(used to create a new branch)<br>
git remote add origin (Used to link local repo to github repo on the internet its not important for you to be the owner of that branch)<br>
<br>
# Linux and its commands<br>
The users data is available in home folder<br>
The commands that we run in linux its files are present in **bin folder**<br>
The  apps such as nginx and users config files such as user groups etc are available in **ETC folder** <br>
The logs,volumes and file such as html file for nginx is stored in **var folder** <br>

# linux commands<br>
**pws**                    (to check present working directory)<br>
**cd**                     (change directory)<br>
**kill -9 processid**      (force stop any process)<br>
**kill processid**         (stop any process)<br>
**ping google.com**        (It will ping google.com)<br>
**grep**                   (grep command is used to match patterns and show it as output)<br>
**ls home | grep ubuntu**  (it will show all the folders or files that are in home folder)<br>
**ping -c 2 google.com**   (It will ping the google.com 2 times)<br>
**ps**                     (shows processes that are running)<br>
**ctrl+c**                 (used to terminate foreground processes)<br>
**ctrl+z**                 (used to stop a foreground process)<br>
**cat newfile.txt**        (This command will shows all the text in the newfile.txt as output)<br>
**touch**                  (touch command is used to create new file (touch newfile.txt) it will create a file with newfile.txt as name)<br>
**touch .newfile.txt** (this command with . in the start of file name will be used to create a hidden file)
**mkdir**                  (this command is used to make new directory or folder like mkdir newfolder)<br>
**ls**                     (list show it shows all the files in a folder or directory like (ls home) this command will show all files folders in home folder)<br>
**ls -l** (to view detailed list of file and folders)
**ls -la** (to view hidden file as well as all other files in detailed view)
**cd..**                   (is used  to go back from current folder to one folder back)<br>
**sudo -i**(change user to root user)<br>
**history** (this command is used to view the commands executed by the user in a session)<br>
**rm** (it is used to remove a file like rm newfile.txt it will remove newfile.txt file)<br>
**rm -r** (-r is for recursive and this command is used for deleting a folder and file)<br>
**mv** (used to move or rename a file or folder)
**sudo usermod -aG kashan(uname) sudo(ugroup)** ( this command is used to add any user to na existing group)
**useradd kashan(username)** (creates a new user but without directory in home)
**useradd -m kashan(username)** (creates a new user with a username directory in home)
**adduser kashan(username)** (creates a user with password and directory)
**groupadd newgroup(groupname)** (creates new group)

# AWS notes<br>
# S3<br>
# S3 Definition<br>
s3 (simple storage service) is a aws service that is used for storing data in the form of objects each file in s3 is stored as an object.<br>
# S3 Classes<br>
S3 has classes according to the need these classes vaires in pricing frequency of data read write and retieval times etc<br>

# EC2<br>
