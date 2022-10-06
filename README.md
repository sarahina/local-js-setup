# Local JS Setup

This is a small repo to help you run JS code more effiently in your local environment

## Prerequisits
You should have Git and NodeJs installed on your local machine. Use the following links to navigate to the download pages and follow the installation instructions for you operating system.
* [Git](https://git-scm.com/downloads)
* [NodeJs](https://nodejs.org/en/download/)

## Verify installations
Use the following **git** commmand to make sure the software is installed and view the **git** version. 

```bash
git --version
```

Installing **NodeJs** also installs a tool called **npm**. Use the following commmand to make sure **npm** is preset on your machine and view the **npm** version. 

```bash
npm --version
```

Use the following commmand to make sure **node** is preset on your machine and view the **node** version. 

```bash
node --version
```
## Project

```bash
├── index.js
├── package.json
├── package-lock.json
├── README.md
└── week1
    ├── operators-end.js
    └── operators-start.js
```



## Dependencies

`package.json` is a special file that allows you to define the library **dependencies** to install. Execute the following comand in the top level directory also known as this project's root directory. This is inside the `local-js-setup` directory/project.

```bash
npm install
```

Alternativally you can install **nodemon** globally on you operating system with the following command.
```bash
npm install -g nodemon
```


### Nodemon

[Nodemon](https://www.npmjs.com/package/nodemon) is a tool that  helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.









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
