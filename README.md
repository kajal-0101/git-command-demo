
# Git Command Demonstartion
This repository is being created for demonstrating basic git commands

Some of the important git commands include:
## Clone
```
git clone <URL of the repository>
```
This command is used to clone the remote repository into the local file system. The <..> message is to be replaced by the URL of the repository to be cloned.

## Log
To get a list of the commits made into the repository, either of the commands may be used
 
 ### verbose generating command
 
 ```
 git log
 ```
 This command generates a verbose output
 
 ### non verbose generating command
 
 ```
 git log --oneline
 ```
 This command generates a non-verbose output
 
 ## Pull
 
 ```
 git pull
 ```
 
 This command can be considered as the combination of commands **git fetch** and **git merge**, as it firstly fetches updated data from the remote repository then merges it with the local repository data. Conflict, if any must be solved manually.
 
 ## Show
 
 ```
 git show <commit-id>
 ```
 
 The above command produces verbose output exhibiting the details of the commit whose id has been passed.
 
 ```
 git show <commit-id> --name-only
 ```
 This command can be executed to produce non-verbose output of the passed commit id
 
 ## Branch
 
```
git branch <branch-name>
```

To create a new branch of the repository the following command must be used. This command creates a local branch. For pushing the **newly** created branch into the remote repository, the below command must be used

