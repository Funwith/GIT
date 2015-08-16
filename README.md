# gitmaster


## Linux installation

+ Git website: http://git-scm.com (Source code manager)

+ Terminal: 

    Debian/Ubuntu `sudo apt-get install git`
    
    Fedora: `yum install git`
    
+ Check install on your operator system

`which git` or `git --version`

## Configuration

+ System

+ User

    `$ cat ~/.gitconfig`
    
    Example: 
    
    ```
    [user]
    
     	email = 0xgi@github.com
     	
     	name = HaiLP
     	
     [core]
     
     	excludesfile = /home/flash/.gitignore_global
    ```
     	
    Git command: 
    
    + git config --global user.name "Flash"     `git config user.name`
    
    + git config --global user.email "0xgi@github.com"      `git config user.email`
    
    `git config --list`
    
    
    Advanced: 
    
    + `git config --global core.editor "vim"`
    
    + `git config --global color.ui true`
    
    `$ cat ~/.gitconfig`
    
    Example:
    
    ```
    [user]
     	email = 0xgi@github.com
     	
     	name = HaiLP
     	
     [core]
     
     	excludesfile = /home/flash/.gitignore_global
     	
     	editor = vim
     	
     [color]
     
     	ui = true
    ```
     	
+ Project

    my_project/.git/config 
    
## Git auto-completion

[git completion](https://github.com/git/git/blob/master/contrib/completion/git-completion.bash)


## Initializing a repository

+ Start doing it tracking project
    
    `git init`
    
+ Understanding where Git files are the stored

    `git add .` or `git add fileName`
    
    (Use `git reset HEAD <file>...` to unstage)

+ Viewing tracking files commit your project    
    
    `git status`
    
+ Writing commit messages

    `git commit -m "Update new feature"`
    
+ Viewing the commit log

    `git log`
    
## Git concepts and Architecture

+ Three tree architecture

    ![Thee tree architecture github](https://raw.githubusercontent.com/0xgi/Docs/66844f1933566728fbded475e323faf163e5029f/images/git-three-tree.png)
    
+ The git workflow

    ![Git workflow](https://raw.githubusercontent.com/0xgi/Docs/5adfb6cd9f5798a599da11782763bacb46b96d90/images/git-three-tree-2.png)

+ Using hash values (SHA-1)



    
    



