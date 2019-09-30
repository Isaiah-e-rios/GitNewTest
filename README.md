# GitNewTest
Git setup:

install Vs code:
    https://code.visualstudio.com/
install git:
    https://git-scm.com/

i made a collision here.

once both installed copy:
    git@github.com:Isaiah-e-rios/GitNewTest.git

then go to desired file destination right click and press git Bash
next enter command git clone and paste coppied ssh

now open vs code and open your folder.
open terminal and git pull to ensure you are up to date.

notable git commands:(Some Please add as learned)
    git add <file name>, <another file name> //add one or multiple files
    git add .  // stages all files for commit
    
    git commit -m "message to commit" // always write a short but useful commit message

    git pull //pulls newest uploaded version

    git push //uploads commited files to github


Order of operations:

    add    // stage new files to be committed

    commit  // commits changes also adds small note / comment on what was done
    
    pull   // pull to ensure that there are no conflicts with current version on git
           // if conflicts occur fix and start process over (add, commit, and pull) 
    
    push    // once all conflicts resolved push your code to master branch.
