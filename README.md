#  Node.js Project Structure

```
    NodeJS and NPM.
    MVC architecture (Model, View, and Controllers).
    REST APIs.
```

## Node JS project structure is important
    It organizes the code into separate files, folders, and subfolders

    . Bundle similar logic in the same folder
    . The controllers should be thin
    . Separate the database logic and business logic
    . Use a Routes file to make API calls
    . Node Modules should be in the root folder
    . Environment Variables in .env file
    . gitignore file should be used to prevent unnecessary files to be shared
    . Test Files should be included next to the logic files

## File Structure

    . Config - Contains the database and server configuration files.
    . Controllers - Contains the javascript controller files.
    . Middleware - Contains the middleware files for authentication and validation.
    . Migrations - Contains the migration class files of our database ( SQL is used).
    . Models - Contains the model class files created by our ORM. ( here SQL )
    . Node_Modules - Packages and dependencies installed using NPM.
    . Routers - Contains router files used to route requests to controllers. (API calls )
    . Seeders - Files used for initializing the database tables with data.( created by the ORM).
    . Services - Files with actual business logic used to access the database.
    . .env file used to store environment variables.
    . .gitignore file used to mention the modules which will be ignored by GIT.
    . package-lock.json & package.json are used to store all metadata in JSON format.
    . server.js -starting point of our application with calls to all the modules and functions. Running this file starts the server.
    

A good node js project structure has code segregated into files, folders, and sub-folders.This makes the code more readable and easier to maintain.

Similar pieces of code or codes with similar logic should be grouped under the same folder. For eg., All services should come under one services folder.

Business Logic should be separated from controllers.
Database Logic should be separated from services.

Node Modules, config files, JSON files, and environment files also must have a proper structure in the node js application.

    