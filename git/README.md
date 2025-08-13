# git

### What is git?  
Git is a distributed version control system used to track changes in code and collaborate with other developers.  

### Key Features:  
- Track history of every change  
- Branching and merging for isolated feature development  
- Revert to previous versions safely  
- Works fast and offline

Before git, we have a Centralized Version Control System, In a **centralized system**, there is one central server that stores the entire codebase. Everyone connects to that server to get or update the code.  

### How it works:  
- Developers must be online to access code.  
- If the central server is down or lost, all data may be lost.  
- Example: Subversion (SVN)
  
### Distributed Version Control System  

A Distributed Version Control System is a system where every developer has a full copy of the entire repository, including the entire history of all changes — not just the latest version.

### How it works:  
- You clone the repository → you get the whole history  
- You commit changes locally → even without internet  
- You later push your changes to a shared server (like GitHub or GitLab)  
- Others can pull changes into their own copy

------------------------------------------------------------------------------------------------------------

# How to install git in Linux machine

Below are the steps to follow to install git in your linux machine.
<br>
1. Updaate your system  
sudo dnf update -y  
2. Install git using DNF  
sudo dnf install git -y  
3. Veirify the version, if it installed succesfully then it will show us the installed version details  
git --version  
<br>

# How to install git in Windows machine  

1. Click on the below official link 
https://git-scm.com/downloads/win  
2. Download the installer file  
3. Go through the setup wizard    
4. Now after successfull installation verify the git version by running the below command  
git --version

----------------------------------------------------------------------------------------------------------------------------

# Now we will learn how to initialize git and work with commands  

1. Create a directory for git project
mkdir git-project  
2. Ran the command below to initialize a git repository
git init  
3. Git will create a hidden .git/ directory in my-project/, like this:
```bash   
   my-project/
├── .git/
├── (your files go here)
```
The .git/ folder contains all the internal Git data, including:  
- History  
- Configuration
- Branches
- Logs
- Object storage

### Now we have installed git in our machine and intiailized the git, now lets see how to Add files, commit files, push files to git  

1. Create a file
sample.txt  
2. add content to the file
3. Now ran the below command and it will give you current changes of the file  
git status  
4. Now we need to run below command  
git add . or git add filename
It will stage the file, which means we are telling the git to include this files in our next commit.  
6. Now use git commit   
git commit -m "message"  
It will commit the changes to local repo
