# Git Notes

**What is Git?**

Git is a DVSC (Distributed Version Control System) that stores data in a file system that is comprised of snapshots. Everytime you 
make a change to a project (you commit it) git takes a snapshot of that commit for a reference point.

**Local Operations**

Git relies on local ops, becasue most of the neccesary info can be found from local resources. Allowing for project efficiency
because the project resides on a local disk. Which eliminates the need to retrieve history information from the server, 
and allowing you to continue work on a project even when not online or on a VPN.

**States** 

Git resides in three states - Committed, modified, and staged 

    Committed: Data is securely stored in a local database

    Modified: File has been changed but not committed to the database

    Staged: Flagged a file’s changed version to be committed in the next snapshot
    
# Installing Git for Mac OS X

The easiest way to install git on a Mac is to install it on your terminal. Go to spotlight -> type in "Terminal" if git is not
installed, you'll be prompted to install it. Then you can rock n roll.

# Navigating Git

* List - Key Command: ls: this allows you to see your files
* Make Directory - Key Command: mkdir: this allows you to make a new file inside git ex: mkdir 2020
* Change Directory -  Key Command: cd: this allows you to change command ex: cd 2020
* Typing git status in terminal allows you to check your file status 

# Tracking and Staging a New File

_in terminal type in these commands as follows_

**Single File**

* git add filename

**All Files**

* git add *

_Once these commands are executed the files are ready to be commited_

* To commit a file type in your terminal (git commit -m"whatever change you made")

**Push Changes to a Remote Repo**

* in your terminal type (git push origin master)
* This will move all your changes from your local 
