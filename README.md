# Backend Development and APIs

This directory contains the practical boilerplate projects used while completing the Free Code Camp Back End Development and APIs curriculum. Each submodule is a minimal starter app for one of the main topics in the course: package management with npm, building a Node.js and Express server, and working with MongoDB and Mongoose.

## Learning goals

This collection is intended to help you practice:

- managing dependencies and scripts with npm
- creating and running a basic Express server
- using middleware, routes, and static assets
- connecting an application to MongoDB with Mongoose
- working with environment variables and project boilerplate

## Recommended environments

The course can be completed in several environments, including:

1. [GitHub Codespaces](https://www.freecodecamp.org/news/learn-programming-in-your-browser-the-right-way/)
2. [Ona](https://forum.freecodecamp.org/t/relational-database-curriculum-in-ona/760889)
3. [Local development](https://www.freecodecamp.org/news/how-to-run-the-freecodecamp-backend-challenges-locally/)

I completed the curriculum locally and also used GitHub Codespaces during the process.

## Submodule overview

For cleaner development, the boilerplate code for each challenge was split into separate submodules:

- [boilerplate-npm](boilerplate-npm/): introduces package management, dependency installation, and npm scripts.
- [boilerplate-express](boilerplate-express/): provides a starter Express app for routing, middleware, and static file serving.
- [boilerplate-mongomongoose](boilerplate-mongomongoose/): provides the base project for connecting to MongoDB with Mongoose and creating models.

## How to use each submodule

From each submodule directory, install dependencies and start the app:

```bash
npm install
npm start
```

### boilerplate-npm

This folder is the starting point for the npm package management lessons. It focuses on:

- the structure of package.json
- dependency versions and installation
- npm scripts such as start

### boilerplate-express

This folder is the starter project for the Basic Node and Express challenges. It focuses on:

- creating an Express application
- serving static assets from the public and views folders
- handling simple routes and middleware
- using environment variables such as PORT

### boilerplate-mongomongoose

This folder is the starter project for the MongoDB and Mongoose lessons. It focuses on:

- connecting an app to MongoDB through Mongoose
- defining and using a model for data persistence
- working with environment variables through a sample.env file
- handling request routes that interact with the database

## File structure

```text
Backend-Development-and-APIs/
├── boilerplate-express/
│   ├── public/
│   ├── views/
│   ├── myApp.js
│   └── server.js
├── boilerplate-mongomongoose/
│   ├── views/
│   ├── myApp.js
│   ├── sample.env
│   └── server.js
├── boilerplate-npm/
│   ├── public/
│   ├── views/
│   └── server.js
└── README.md
```

> Note: package-lock files, environment files, and other supporting config files are omitted here for clarity.

## Notes

A large portion of the original curriculum content is now considered legacy or outdated, especially where older Node.js and Express patterns were used. The projects are still useful as a foundation for understanding core backend concepts.

## Future work

Possible next steps include:

- updating the projects to modern Express and Mongoose versions
- replacing callback-based patterns with async/await and Promises
- adding clearer examples for error handling and validation
- introducing modern tooling such as ESLint and environment-safe configuration
