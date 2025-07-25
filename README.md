Version control is a system that allows developers to track and manage their codes. It also allows user to compare changes and collaborate. Version control  can be local,distributed or decentralized.

Importance of version control
 - Collaboration: Developers can work on the same project at the same time.
 - Version tracking: Every change is recorded in case there is a need to visit the previous versions
 - Branching: This helps to work on a particular features withot affecting the main code. Either to fix a bug or to update a particular area.

 Git is a distributed control version that helps developers to track their codebases, manage them and collaborate with others. It is open source and free, it allows for bramching, merging, makes collaboration easier and it is offline.

Github is a web-based version control that host Git repositories and provides nd interface to manage code, share code,issue tracking, collaboration and do so many other things.


Difference between git and Github
1. Git is  accessed from a local machine while Github is a web-based (i.e.it is accessed remotely).
2. Git is a version control systems while Github is a host repositories.

Comprehensive Git and Github setup for Beginners
- Setup for Git
On Windows: Download from git-scm.com
On Linux, use this command: sudo apt install git
On Mac, use this command: brew install git

- After installation, Configure git using these command:
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"
git config --global init.defaultBranch main 
This sets your name,email address and your Branch for all Git projects.

-Initialize repository using: git init.


- Setup for Github 
Create a github account by going to https://github.com.
Read the instruction there and sign up for a free account.

- Create a New Repository on GitHub
Go to GitHub, click New then name it git-setup.
Do not select "Initialize with README" (because you already have one local machine) then click create repository.
It displays information and guidelines for creating a new repository using a command line or pushing an existing repository from a command line. 
Here, I am pushing so I will use the commands for it and run them in local machine.

-  Link local repository to GitHub
Copy the repository link (I am using ssh for this setup),So copy each of the commands there and run them.
