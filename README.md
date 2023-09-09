[] install express
[] add npm scripts
[] add / and /health routes
[] push to git


1. If you are working in a new project
    - Create new folder
    - Change your directory to the new project directory
    - Intialize git project
        ```bash
        git init
        ```
    - Configure username and email
        ```bash
        git config user.name "John Doe"
        git config user.email "johndoe@example.com"
        ```
    - Configure remote
        - Create repository in github
        - follow the instruction in the step 2 i.e push an exisiting repo 
        ```bash
        git remote add origin https://github.com/KNSSMANIKANTA/NodeJS-REST-API-Server.git
        git branch -M main
        git push -u origin main
        ```
    - Add the folders and file required
    - > All the above steps should be run only once during the setup
    - ==================
    - Check the status
        ```bash
        git status
        git add . #To all the files and folders
        git status #To recheck about what your about to commit
        git commit -m "Your message"
        git log --stat #press q to exit this command
        git push
        ```
   
