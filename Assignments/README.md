# Assignments
DataScience Assignments


*Practice Checkout/pull - git pull https://github.com/abchiSuriamoorthy/Assignments.git

*Practice Checkin/push - https://github.com/abchiSuriamoorthy/Assignments.git


### change directory
aaa@bbb /
$ cd ~/documents

###Print working directory
aaa@bbb ~/documents
$ pwd
/c/Users/abc/documents

### cd to DataScience
aaa@bbb ~/documents
$ cd DataScience

### Initialize empty repository on local
aaa@bbb ~/documents/DataScience
$ git init
Initialized empty Git repository in C:/Users/abc/documents/DataScience/.git/
## Logon to GitHub using web browser and Create new repo 'Assignments'
###Check out from Hub , by branching off of the master
aaa@bbb ~/documents/DataScience (master)
$ git checkout -b master
Switched to a new branch 'master'

### issue a pull request (checkout from hub) 
aaa@bbb ~/documents/DataScience (master)
$ git pull https://github.com/abchiSuriamoorthy/Assignments.git

### The message says that checkout was successfull
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/abchiSuriamoorthy/Assignments
 * branch            HEAD       -> FETCH_HEAD

### Print working directory
aaa@bbb ~/documents/DataScience (master)
$ pwd
/c/Users/abc/documents/DataScience

### cd to Assignments folder/directory
aaa@bbb ~/documents/DataScience (master)
$ cd Assignments
aaa@bbb ~/documents/DataScience/Assignments (master)

### Verify that you are in the Assignments dir
$ pwd
/c/Users/abc/documents/DataScience/Assignments

## Open up the File and edit.
###Now add all the changes to git local
aaa@bbb ~/documents/DataScience/Assignments (master)
$ git add -A

### Commit the changes 
aaa@bbb ~/documents/DataScience/Assignments (master)
$ git commit -m 'checked out from hub and edited the readme file'
[master e342c66] checked out from hub and edited the readme file
 2 files changed, 7 insertions(+), 2 deletions(-)
 create mode 100644 Assignments/README.md
 delete mode 100644 README.md

##Push/Checkin the chagnes to Hub
aaa@bbb ~/documents/DataScience/Assignments (master)
$ git push https://github.com/abchiSuriamoorthy/Assignments.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/abchiSuriamoorthy/Assignments.g                                                                                                                it master


aaa@bbb ~/documents/DataScience/Assignments (master)
$  git push --set-upstream https://github.com/abchiSuriamoorthy/Assignments.git master
Counting objects: 4, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 437 bytes | 0 bytes/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/abchiSuriamoorthy/Assignments.git
   6044b41..e342c66  master -> master
Branch master set up to track remote branch master from https://github.com/abchiSuriamoorthy/Assignments.git.

##To Verify that local and HUb are in sync
aaa@bbb ~/documents/DataScience/Assignments (master)
$ git pull https://github.com/abchiSuriamoorthy/Assignments.git
From https://github.com/abchiSuriamoorthy/Assignments
 * branch            master     -> FETCH_HEAD
Already up-to-date.

aaa@bbb ~/documents/DataScience/Assignments (master)
$



