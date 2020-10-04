# 3. NodeJS: Express Routes Stack

Your company is creating an internal project management tool, As the NodeJS developer in the company, you have been given the task to write a basic Express app that implements three routes to return the project's data to the client.

Each project object is a JSON object with the following keys:

1. `name` - The name of the project. [STRING]
2. `id` - The unique ID of the project.
3. `isActive` - A boolean value denoting whether the project is still active [BOOLEAN]

The list of projects in the project.js file can be retrieved by calling the getProjects function from the data-store.js module.

```
var data = require('../data-store');
var projects = data.getProjects();
```

### **Software Instructions**

The questions(s) requires **Node 8 LTS or above**.

- https://nodejs.org/en/downloads/

### **Git Instructions**

Use the following commaands to work with this project

Run

```
npm start
```

Test

```
npm test
```

Install

```
npm install
```
