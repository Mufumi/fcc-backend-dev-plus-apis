# Backend Development and elementary APIs

This is a collection of the practical components of the V8 Back End Development and APIs certification from Free Code Camp. 

## Lab Environment

This course can be run on multiple environments and FCC recommended running it through the following environments

1. [Ona](https://forum.freecodecamp.org/t/relational-database-curriculum-in-ona/760889)
2. [Github's Codespaces](https://www.freecodecamp.org/news/learn-programming-in-your-browser-the-right-way/)
3. [Local](https://www.freecodecamp.org/news/how-to-run-the-freecodecamp-backend-challenges-locally/)

After using all three options, however, I completed it on Github's Codespaces.

## Submodule structure

For cleaner development, I chose to fork the boilerplate repos for the [NPM](https://github.com/freeCodeCamp/boilerplate-npm/), [Express](https://github.com/freeCodeCamp/boilerplate-express/) and [Mongo-Mongoose](https://github.com/freeCodeCamp/boilerplate-mongomongoose/) sections.

## File Structure

```
fcc-backend-dev-plus-apis/
├── boilerplate-express/             # Express submodule
|  |─── public/
│  │   └── styles.css 
|  |─── views/
│  │   └── index.html
|  |─── myApp.js
|  └─── server.js
├── boilerplate-mongomongoose/       # Mongo-mongoose submodule
|  |─── views/
│  │   └── index.html
|  |─── myApp.js
|  |─── sample.env
|  └─── server.js
├── boilerplate-npm/                 # npm submodule
|  |─── public/
│  │   └── styles.css 
|  |─── views/
│  │   └── index.html
|  └─── server.js
└── README            # Primary README
```
**Note:** .gitignore, .gitpod.yml, README, lock and package files have been omitted from structure

## Notes

Deprecation - A bulk of the sections covered content that was either deprecated or legacy.

## Future Work

Consider implementing the sections with more modern libraries(mongoose), objects (Promise), statements (try catch), design patterns (Error-First Callback)
