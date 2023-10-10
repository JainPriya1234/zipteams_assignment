# zipteams_assignment
TODO-List API

---
 RESTful API for a simple "To-Do List" application using Node.js, PostgreSQL for data storage, and AWS hosted [link](http://35.154.71.190:8000)

# Key Features
- Implement CRUD (Create, Read, Update, Delete) operations for To-Do list items.
- Deploy the application to AWS using an AWS EC2 instances
- Error handle on each section and seprate Error handler
- Seprate handler for Success Responce
- Used PostgreSQL for handling Database
- Postman Collection is Also Added for better Understanding

  
### END POINTS

- `/add/task` For creating New Task
- `getall` Get All Task
- `update/task`  Update Task By Id
- `remove` Remove Task By Id
- `get` Get a Single Task


### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

## Install

    $ git clone https://github.com/YOUR_USERNAME/PROJECT_TITLE
    $ cd PROJECT_TITLE
    $ yarn install

## Configure app

Open `a/nice/path/to/a.file` then edit it with your settings. You will need:

- A setting;
- Another setting;
- One more setting;

## Running the project

    $ yarn start

## Simple build for production

    $ yarn build
