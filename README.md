# Local JS Setup

This is a small repo to help you run JS code more effiently in your local environment

## Prerequisits
* (Git)[https://git-scm.com/downloads]
* (NodeJs)[https://nodejs.org/en/download/]


You should have Git and NodeJs installed on your local machine
-Install pre-requisits: navigate to the Git/NodeJS download sites and follow the instructions for you OS
--Git - https://git-scm.com/downloads
--NodeJS - https://nodejs.org/en/download/

## Test installations
Git - run command: 

```bash
git --version
```


--NodeJs - run command: node --version
--both Git and NodeJS at the same time - run command: git --version && node --version (NOTE: the commands will be run in the order you call them)

Running the applicaion/files

1. install dependencies - run the command: npm install
2. run nodemon - open a terminal in the root of the project and run the following command: nodemon <pathToFile>/<fileName.js>
   For example if your file is in the week1 folder, your command would be nodemon week1/<fileName.js>

   NOTE: running nodemon without a file name specified will run the index.js file, as that is the entry point of the application

   Feel free to us this as your plaground and fork this repo in order to make changes, etc.

   NOTE: I will be keeping this repo in the default state for lessons, so please do not make PR's to the repo.
   If you wish to make changes and push them to your own gihub profile, then you can either fork the repo or change the origin. The command to change the remote url is: git remote set-url <newUrlForYourRepo>. You can find more detailed instructions here: https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories
