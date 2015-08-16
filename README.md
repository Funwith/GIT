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
    
    `[user]
     	email = 0xgi@github.com
     	name = HaiLP
     [core]
     	excludesfile = /home/flash/.gitignore_global`
     	
    Git command: 
    
    + git config --global user.name "Flash"     `git config user.name`
    
    + git config --global user.email "0xgi@github.com"      `git config user.email`
    
    `git config --list`
    
    
    Advanced: 
    
    + `git config --global core.editor "vim"`
    
    + `git config --global color.ui true`
    
    `$ cat ~/.gitconfig`
    
    Example:
    
    `[user]
     	email = 0xgi@github.com
     	name = HaiLP
     [core]
     	excludesfile = /home/flash/.gitignore_global
     	editor = vim
     [color]
     	ui = true`
     	
+ Project

    my_project/.git/config
    



