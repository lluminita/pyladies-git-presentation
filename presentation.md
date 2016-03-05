Who we are
==========
- Website:Pyladies Berlin
- Meetup: http://www.meetup.com/PyLadies-Berlin/
- Youtube: https://www.youtube.com/user/PyLadiesBerlin
- Twitter: https://twitter.com/PyLadiesBer
- GitHub: https://github.com/PyLadiesBerlin/materials

Good old times
==============

   ReadMe1.txt  
   ReadMe2.txt  
   ReadMe3.txt


Good old times
==============

   ReadMe.txt  

But what is git?	
================
- Open source
- Fully distributed
- Fast
- Support for non-linear development
- Handles big projects

Collaboration platforms
=======================
   https://github.com/  
   https://github.com/explore  
   https://github.com/integrations  
   https://git-lfs.github.com/ - large repos  

   https://bitbucket.org - more private repos for free  

Installing Git
==============
####Step: Install Git
   **Windows**: It's recommended to download GitHub for Windows, which includes Git and has an easier install: windows.github.com. Use the Git Shell for your terminal.  
   **Mac**: You can also download GitHub for Mac, which includes Git, mac.github.com (from Preferences, select the command line tools install), or download Git by itself at: git-scm.com/downloads and follow the installation instructions.  
   **Linux: Debian-based Distribution**
       $ sudo apt-get install git-all  
   **Linux: Febora-based Distribution**
       $ sudo yum install git-all  

Configure Git
=============
   git config --global user.name "John Doe"  

   git config --global user.email johndoe@example.com

Checking your settings
=====================
   git config --list  

   git config user.name

Let the game begin
==================
##### Create a new directory  
  * mkdir hello  
  * cd hello   

##### Create a local repository  
  * git init   

##### Create a new file   
  * <favourite_editor> foo.txt   

##### Add the file to the staging area  
  * git add foo.txt

Git states & sections
=====================
   modified - working directory  
   staged - staging area  
       - git add <file_name>  
   committed - .git directory  
       - git commit

http://www.git-scm.com/book/en/v2/Getting-Started-Git-Basics#The-Three-States

Let the game begin
==================
##### Check the status of the files
  * git status

##### Commit the files
  * git commit -m "First Commit" 

##### Check the history
  * git log

##### Create a new branch and checkout the branch
  * git branch feature
  * git checkout feature (git checkout -b <new_branch>)
  * <favourite_editor>bar.txt - changing the file
  * git status
  * git add -p bar.txt
  * git commit -m “Second commit”
  * git checkout master
  * git merge feature

  * git checkout feature
  * vim foo.txt
  * git add foo.txt
  * git commit -m “commited foo file from feature branch”

##### We need to fix a bug in master
  * git checkout master
  * vim bar.txt
  * git add bar.txt
  * git commit -m “fix bug in master”

  * git log --graph --decorate

###### Let’s merge our master with the bug fix into feature branch and test our feature with the new changes.
  * git checkout feature
  * git merge master

Sharing our work
================
  * https://github.com/

Alternative to github, more private repos for free
  * https://bitbucket.org

GitHub
======
Upload the repository to GitHub
  * git push

You want to work on an existing project?
  * Fork it
  * git clone git@github.com:whatever folder-name

Useful links
============
Git documentation:  
http://www.git-scm.com/

short guides:  
https://try.github.io//levels/1/challenges/1  
https://guides.github.com/

tools for learning about branching:  
http://pcottle.github.io/learnGitBranching/  
http://onlywei.github.io/explain-git-with-d3/#branch

Repos history visualization
  * gitk

helpful commands (cheat sheet):  
https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf











