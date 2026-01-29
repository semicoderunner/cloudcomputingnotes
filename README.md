# cloudcomputingnotes
cloud computing notes<br>
# Git commands<br>
**git clone gitlink**(to clone a repo on local pc)
**git push** (for pushing any file to a repo)<br>
**git add** (to add any file to staging)<br>
**git pull** it is used to pull changes from the online repo and also merges them<br>
**git tag v3.0.0 551dc8c** this command is used for adding tag to any commit<br>
**git branch remote add origin repolink** this command is used to link local repo with remote repo<br>
**git switch branchname**this command is used to switch branches <br>
**git branch -d branchname** this command is used to delete a branch<br>
**git checkout -b featurebranch** this command is used to make a new branch and switch to that branch <br>
**git push origin main** used to mush local branches to main<br>
**git tag v1.0.0** this command is used to tag latest commit <br>
**git tag v1.0.0 #commmithash**  this command is used tag commit according to hash<br>
**git revert hash** (to revert a commit)<br>
**git fetch** (to upate repo with the repo on the remote)<br>
**git fetch origin**<br>
**git branch -r**(for checking the remote branchs)<br>
**git branch -a**(for checking all branches)<br>
**git branch -d branchname** for deleting a branch in repo.
**git log --oneline** this command is used to check the commits with hash 
**git status** (for checking the status of a branch if any file is added changed or deleted etc)<br>
**git checkout branchname** (used to navigate to branches)<br>
**git branch newbranch**(used to create a new branch)<br>
**git log** git log command is used to view all commits <br>
**git remote add origin** (Used to link local repo to github repo on the internet its not important for you to be the owner of that branch)<br>
<br>
**git show** this command shows the details of a object or branch etc.
**git commit -m"message here"** <br>
# Linux
## Linux and its commands<br>
**What is linux distribution?**<br>
linus  is free open source anyone can modify it for their use so a linux that is made for specific purpose and distributed is called a distribution for example debian distributes stability .
linux distribution means that a os is based on a specific family like we say that ubuntu is a distribution of debian.
There are main 6  families of linux namely <br>
1.Debian Family<br>
2.Red Hat Family<br>
3.Arch Family<br>
4.SUSE Family  <br>
5.Gentoo Family<br>
6.Slackware Family<br>
these families differ in package manager like debian uses apt package manager and redhat uses yum/dnf package manager.<br>
other differences can be the preconfigured tools when you first install them like ubuntu has mostly things installed like wifi dirvers etc but arc linux does not have any thing its like a empty canvas<br>
**What is linux flavour?** <br>
The flavour is the official version of a distribution for example flavours of ubuntu are kubuntu lubuntu share same base as ubuntu but differ in cosmetic changes.<br>
**In terms of linux what does ubuntu Based on means?** <br>
In terms of linux based on means that a specific os is built with another os as base os like Ubuntu → based on Debian Linux Mint → based on Ubuntu<br>
The users data is available in home folder<br>
The commands that we run in linux its files are present in **bin folder**<br>
The  apps such as nginx and users config files such as user groups etc are available in **ETC folder** <br>
The logs,volumes and file such as html file for nginx is stored in **var folder** <br>
# Linux file system
Linux file system is a hyrerical tree like file system which starts from / root and then navigates to /etc /home etc In linux every device is considered as a file
**Relative path** It starts from starting point root making easy to understand like /home/ubuntu/newfolder <br>

**Absolute path** It starts from current location in which user is like if user is in ubuntu the path saths from /ubuntu/newfolder<br>
# Users & Groups

# linux commands<br>
**pws**                    (to check present working directory)<br>
**cd**                     (change directory)<br>
**kill -9 processid**      (force stop any process)<br>
**kill processid**         (stop any process)<br>
**ping google.com**        (It will ping google.com)<br>
**grep**                   (grep command is used to match patterns and show it as output)<br>
**egrep "loans?" file.txt** (this command is for nextended regix expressins now this command will show all the words with loan and loans )
**Zgrep "loan" file.txt.gz**  (this command is used to match pattern and get output from a zip file)<br>
**sort file.txt** (this command shows output sorted output)<br>
**sort -n file.txt** (this command sorts the numeric data and shows the output)<br>
**cut -c 1-5 file.txt** (this command is used to get specific part of text from file like in the given this prints the first 5 characters from the file)<br>
**cut -b 1-3,5-7 state.txt** this commands is use to get bytes from text file.<br>
**cut -b -3 file.txt** (this command returns first 3 bytes from each line)<br>
**cut -d " " -f 1 state.txt** this command is used to get  words from each line until delimiter encounters<br>
**Realworld example of cut command** can be to get the name or id of the users from the /bin/bash file that have bash access .<br>
<img width="524" height="178" alt="image" src="https://github.com/user-attachments/assets/082fc4ad-70bd-4469-83de-4c519b3197d9" /><br>
**uniq file.txt** (this command skips the adjcent duplicte words and prints the rest) <br>
**sed 's/apple/saib/' file.txt** (sed wroks as a noninteractive text editor this command is used to replace words and show as output)<br>
Insert text before a line **sed '1i\newtext' newfile.txt**<br>
Insert text after a line **sed '1a\newtext' newfile.txt**<br>

replace string **sed -i 's/apple/saib/' file.txt** (this command is used to relace words and save it in the file without showing output)<br>
delete **sed '1d' sortfile.txt** (delete specific line by number)
delete **sed -i '/apple/d' file.txt** (this command deletes the word apply in the file)
print **sed -n '/32/p' sortfile.txt** ( this command is used to print a line that matches the pattern)
**ls home | grep ubuntu**  (it will show all the folders or files that are in home folder)<br>
**pipeline command**<br>
**mkdir newdir |touch newfile.txt** (these 2  commands with  pipeline will execute both commands at the same time)
**Change timezone** in linux we can chnage time zone using timezonectl set-timezone Asia/Karachi(any time zone).
**NTP vs Chrony** Ntp and chrony are both time sync utility ntp is old utility and chrony is new utility for sync time its light weight and fast 
Ntp is used in old systems servers.its prefered to use chrony unless task is specifically on old system.
**chronyd setup** this command is used to check the installation of the utility chrony if its intalled or not.
**grep -i** -i flag is used to remove case sensitivity now it brings all the pattern even if its in capital or small letter that matches. <br>
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
**mv** (used to move or rename a file or folder)<br>
**sudo usermod -aG kashan(uname) sudo(ugroup)** ( this command is used to add any user to na existing group)<br>
**useradd kashan(username)** (creates a new user but without directory in home)<br>
**useradd -m kashan(username)** (creates a new user with a username directory in home)<br>
**adduser kashan(username)** (creates a user with password and directory)<br>
**groupadd newgroup(groupname)** (creates new group)<br>
**df** (used to check free space in the disk)<br>
**du newfile(filename)** (used to check the space  a file or folder is taking on disk)<br>
**du -sh newfile (filename)** (this command is used to check size of the file in human summarized view <br>
**du -h newfile(filename)** (du with -h flag is for human readable form of the result of du we can add other flags **-ah** for checking the space with list of the files or folders present in that folder **-sh** its another flag that stands for sumarized human readable it shows sumarized human readable view)<br>
**echo "text" > newfile.txt** (this command is used to insert text to file but i overrides the existing text) <br>
**echo "text" >> newfile.txt** (this command is used to insert text to file but it appends the text to the next line)<br>
**gzip file.txt** (this command is used to zip a file)<br>
**zcat file.txt** (this command is used to show the test of a zip file) <br>
**gunzip file.txt.gz** (this command is used to unzip a zip file)<br>
gzip does not works on directories.
wc file.txt (this command is used to count lines words and bytes of characters)<br>
1.number of lines<br>
2.number of words<br>
3.number of bytes<br>
<img width="345" height="41" alt="image" src="https://github.com/user-attachments/assets/2fb5d7c3-55a5-4da4-85df-d64882b475bc" />
<br>

wc -l  file.txt (this command is used to count the number of lines in a file) <br>

**awk** this commaand is used to filter the output 
**awk usage**  ps -ef | awk -F" " '{print $2}' here we hare printing all the column 2 and each column is saparated by a space<br>
<img width="818" height="136" alt="image" src="https://github.com/user-attachments/assets/b634f437-3410-407f-8b7c-1e3f2c2ac285" /><br>
**ln file1 file2** hardlink this command is used to create a linked file in this case if file1 exist it will create a file2 with same data as file1 and it will be synced to changes if we add any change to file1 or file2 both will bw synced.<br>
**ln -s file1 file2** this is used to create a softlink in our command a link file2 is created that points to the address of the file2  if we delete file 1 file 2 is lost <br>as its a address or link to file1.<br>
**Remove user for group in cent os command** "gpasswd -d username groupname"<br>
# zip 
zip command is used to zip compress directories 
# unzip
this command is used to unzip or decompress a ziped file.
# tar
gzip does not works on directories so if we want to archive a directory with all files in it we use tar 
# etc/hosts file importance
linux system searches in /etc/hosts for resolving hostname (converting hostname to ip so computer knows where to connect)<br>>
like if we want to ping google.com it will not work if hostname is not maped we have to map that is /etc/hosts file like 8.8.8.8 google.com and www.google.com and ping then<br> it will work without any issue.<br>
# /etc/resolv.conf file importance <br>
**/etc/resolv.conf = “Where should I ask when I need to resolve a hostname?”** <br>
if the system does not finds dns maping in /etc/hosts file it sends a request to nameservers listed in the resolv.conf file and gets the ip address back.like nameserver of<br> google nameserver 8.8.8.8 now when we type ping youtube.com we will be able to ping using google public dns.<br>
**SELinux** (what it is, enable/disable temporary/permanent)
SE linux  is a kernel security module that is responsible for mandatory access control for strict permissions it has 3 modes  Enforcing Permissive Disable 
**Enforcing** In this mode the selinux saves logs and blocks access .
if selinux is in enforcing mode and we try to change the password for the root user without making /.autorelabel file then it will restrict all uses from logging in the system.
**scp** this command is used to copy paste any file from to linux or windows.
**rsync**  
**Permissive** In this mode the selinux saves logs only does not blocks user.
if we try to change the password using emergency mode it will allow without any issue but will log the changes
**Disabled** In this mode the selinux is dispabled does not saves logs or does not blocks access.
in this mode its disabled perminently.
**Break root password (rescue mode)**
restart system using init 6
Go in grub menu and press e now edit the initial executable commands write rw and init=/bin/bash then ctrl+x it will get you to bash terminal now first make a .autorelable file which will tell selinux that a change is done in the linux file now run command passwd command and type new paassword now reboot by command exec /sbin/init your password is resetted.
# Shell Scripting<br>
It is used for task automation for example if we want to install any app like nginx <br>
Bash does not needs variable type we can store any type of data so its dynamic by default it treats variable as strings
# Common for every linux script<br>
first line of the file is !/bin/bash <br>
after that we can write any linux command we want to execute line apt update service nginx status etc<br>
the file name should end with .sh extension and to run this script we simmple tyoe ./ at the start of the file but remember to give it executable permission by chmod 777<br>
# debug mode
set -x (trace mode) to turn on debug mode it shows each command before execution for easy debugging
set +x debugging mode disabled
set -e exit the script if error exist
set -o pipeline fail

# condition statements in linux<br>
#!/bin/bash<br>
a=20<br>
b=20<br>
if [ "$b" -gt "$a" ] ; then<br>
echo "b is Greater than a $b"<br>
elif [ "$a" -gt "$b" ] ; then<br>
echo "a is Greater then b $a"<br>
else<br>
echo "equal $a $b"<br>
fi<br>
<br><br><br>
# Linux script with set -x set -e set -o commands

#!/bin/bash
set -x # used for debugging the script it shows each command that is run in each step before output of the command
set -e # used to exit script if there is an error in script
set -o # used to exit script if there is an error in pipeline
a=20
b=2
ls -la | grep -i test
if [ "$b" -gt "$a" ] ; then
echo "b is Greater than a $b"
elif [ "$a" -gt "$b" ] ; then
echo "a is Greater then b $a"
else
echo "equal $a $b"
fi
# what is crontab
its like a alaram that executes a script on a specific time like if we want to send cpu usage on specific time we use crontab 

# AWS notes<br>
# Aws pricing plans
# Saving Plans
Saving plain is as a package for 1 or 3 years it provides a discounted rate per hour on services like ec2 lambda. It gives up to 72% discounted rates.It has 3 payment options full upfront(max disocount) no upfront (Monthly minimum disocunt) partial upfront (Medium disount)
# On demand
In on demand we can get the resources when required and pay for the service as long as we use it
# Dedicated host 
It is a physical system provided to the customer for use.
# spot instance
It provides biding on aws unused resources the resources can be taken back anytime if need arises or the bid is exceded so its not safe to use it for production servers etc.


# S3<br>
# S3 Definition<br>
s3 (simple storage service) is a aws service that is used for storing data in the form of objects each file in s3 is stored as an object.<br>
# S3 Classes<br>
S3 has classes according to the need these classes vaires in pricing frequency of data read write and retieval times etc<br>
# Standard class<br>
It is most expensive class type it allows free retrival and is used when we want to store data that needs frequent acccess like logs.<br>
# Intelligent-Tiering<br>
It is an intelligent class that automatically manages out storage cost by migrating our data to lower cheaper class based on access patterns like if data is frequently <br>accessed it will shirf our data to stand and if data frequency changes back to 30 days it will migrate out data to infrequent class and if data is not accessed for 90 <br>days it will shift to frequent archive and if data is not used for 270 days it will shift our data to glacier deep archive. Advanctage of this classe is automatic cost<br>optimization and free data access even if data is in glacier class.<br>
# Standard infrequent <br>
This class also provides instant retrival like standard class but its cheaper in cost but the retrival cost is not free you can store data in it if the data retrival <br>frequency is about  30 days.<br>
# One zone instant <br>
The data retrival in this class is instant but it does not stores data in 3 zones like in other classes so it is not reliable if that zone is down all the data is not <br>accessable.<br>
# Glacier instant retrival<br>
In this class data can be  accessed instantly but frequency of accessing that data is less like after 90 days. retrival cost is high then standard if<br>
# Glacier Archive <br>
In this class data is stored for long time retrive like about 180 days retrival cost is high.but storage cost is low.<br>
# Glacier Deep Archive <br>
This class provides most cheepest way of storing data but retrival cost is high. Recommended for storing data if retrival frequency is 280 days.12 to 48 hours retrival time.<br>

# EC2<br>
# placement group<br>

This creates a logical rack of ec2s .We can place ec2s in our predefined racks or partitions to improve fault tolerance if we need to improve speed between ec2s we can use <br>cluster partition group and if we need to isolate it we can use partition type.Partition placement group is more scalable then spread placement group that only supports <br>7 ec2s per availability zone.<br>
# Docker commands
**Command to mount a folder to docker container using bind mount**<br>
docker run -it -d -p 81:80 --mount type=bind,source=/home/testuser/newtestdir/volumedire,target=/newfile  --name cont1 nginx<br>
**docker container port expose command**<br>
docker run -it -d -p 81:80 --expose=82 --name cont3 nginx<br>
Docker file difference between Run and Cmd command
Run command executes During image build. used if we want to install a package like apt install nginx.
Cmd command executes when container starts. A docker command can only have only one Cmd if there are multiple then only last will be executed.Its changes cannot be overridden because the changes are stored in the image.
