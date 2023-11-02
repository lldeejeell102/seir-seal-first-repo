# My First Readme

I'm going to use this readme to document what we've learned about github!

- Creating the Repo
    1. create an empty folder `mkdir <name>`
    2. move into that folder `cd <name>`
    3. initialize the repo `git init`

- commit your work periodically
    1. add files to staging `git add .`
    2. commit the files `git commit -m "commit message"`

- setup a remote repo on Github
    1. create a new repo on github (public, no readme)
    2. copy the ssh or https url for the repo
    3. add the remote to your local repo `git remote add origin <url>`
    4. push the commits from local to remote `git push origin main`

- misc commands
    1. see the status of your repo `git status`
    2. see what branch you're on `git branch`
    3. see previous commits `git log`