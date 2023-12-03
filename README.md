# Employee-Tracker-App12

As a way to help business owners and chief executives of small to medium-sized companies keep track of their human resources and departments and easily create or delete records from their databases, we created the CMS (Content Management System) known as Employee Manager. This CLI app will allow to search and modify information in an user-friendly manner without having to deal with complicated SQL queries or use a MySQL shell or GUI. The results of each action taken will be either shown as a formatted table or as a descriptive distictly formatted text that can be easily parsed from the rest of the messages in the terminal. This first foray into CMS gave the author the opportunity to learn more about SQL queries, especially those that depend on prepared statements that can be passed using the .query method of "mysql2", and the use of promises, either by creating Promise objects or chaining .then's in order to handle asynchronous processes started by user inputs (the inputs are handled using the Inquirer interface). Among other things, he practiced the declaration and assignment of environmental variables in order to protect data from reaching unscrupulous hands and the rudiments of creating and displaying ASCII art in the Git Bash terminal.


# Installation

The open source project is available at https://github.com/MaitreePatel08/Employee-Tracker-App12.git . Once you create a directory for it, navigate into it and clone the remote repo, you install the dependencies by entering the command "npm i" in the terminal. After a package-lock.json file with the dependency tree and a node-modules folder has been created, create a .env file in the root folder in order to declare and initialize the environmental variables whose names appear in the 'connection.js' file of the 'config' folder. After that, the app will be ready to use.


