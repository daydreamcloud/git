# Git Basic Get Started

1) Git config command
This command configures the user. The Git config command is the first and necessary command used on the Git command line. This command sets the author name and email address to be used with your commits. Git config is also used in other scenarios.

Syntax

$ git config --global user.name "Cloud"  
$ git config --global user.email "Cloud@daydreamcloud.com"  

2) Git Init command
This command is used to create a local repository.

Syntax
$ git init Demo  
The init command will initialize an empty repository.

3) Git clone command
This command is used to make a copy of a repository from an existing URL. If I want a local copy of my repository from GitHub, this command allows creating a local copy of that repository on your local directory from the repository URL.

Syntax
$ git clone URL  

4) Git add command
This command is used to add one or more files to staging (Index) area.

Syntax
To add one file

$ git add Filename  
To add more than one file

$ git add*  

5) Git commit command
Commit command is used in two scenarios. They are as follows.

Git commit -m

This command changes the head. It records or snapshots the file permanently in the version history with a message.

Syntax
$ git commit -m " Commit Message"  
Git commit -a

This command commits any files added in the repository with git add and also commits any files you've changed since then.

Syntax
$ git commit -a  

6) Git status command
The status command is used to display the state of the working directory and the staging area. It allows you to see which changes have been staged, which haven't, and which files aren?t being tracked by Git. It does not show you any information about the committed project history. For this, you need to use the git log. It also lists the files that you've changed and those you still need to add or commit.

Syntax
$ git status  
