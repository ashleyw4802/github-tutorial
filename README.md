# GitHub Tutorial

_by Ashley Wat_

---
## Git vs. GitHub
Git: a version control that keep “snapshots” or backup of codes

Github: is a website that stores codes in the cloud (requires git to operate) to visually track changes. 
It is easily to collaborate on files and it runs in the command line basic workflow.


---
## Initial Setup
1. Go to Github.com 
2. Press *Sign in* or *Sign up* in the upper right corner to create or log into your account
3. Press the icon and go to setting 
4.
4. Press *SSH and GPG keys*
5. Then create an *SSH key* to connect your Github account with your Cloud9 account 


---
## Repository Setup
Setting up a repository (repo) requires __initializing, adding and commiting.__

    Git init- intializes our git into the repon for version (hiring the family phtographer) 
    Git add- adds any file that is specific into the stae (adding people in the photo)
    Git commit- takes a "snapshot" of the files on stage (taking the picture)


---
## Workflow & Commands


    Git status- to check your current situation/status for your current repository
    Git add- add file to your stage in your repository
    Git commit- when you save what you have from your current file
    Git push- when you push your current commits to github, which can be saved online

---
## Rolling Back Changes

    Undo edit- git checkout -- <file>
    Undo add- git reset HEAD <file>
    Undo commit- git reset --soft HEAD~1
    Undo push- git rm --cached <file>



