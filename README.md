# Walk This Way

## Description

This is the fourteenth assigment from the UConn Coding Boot Camp curriculum. We have covered the following topics thus far: Git, Terminal, GitHub, GitHub Pages, Web Accessibility, HTML, CSS, JavaScript, jQuery, Bootstrap, DOM Traversal, Web APIs, Third-Party APIs, Server-Side APIs, Node.js, Inquirer.js, and Express.js.

Within the last two weeks the following topics have been introduced: MySQL database management system (DBMS) - the most popular Structured Query Language (SQL) relational database, MySQL Shell, Model-View-Controller (MVC) design pattern framework, Handlebars.js template engine, Object Relational-Mapping (ORM) to create resuable methods for querying our database.

View the tutorial [here](google docs link)

## Table of Contents

- [Goals](#goals)
- [Instructions](#instructions)
- [Starter Code](#starter-code)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Business Context](#business-context)
- [Definitions](#definitions)
<!--
- [Installation](#installation)-->
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Goals

1. Inspect starter code within the `Develop` folder.

2. Get an understanding of each file's responsibility.

3. Create a GoogleDoc

4. Write a tutorial explaining _every_ file and its purpose [in GoogleDoc] .

5. Add instructions for how you could add changes to it [at end of tutorial in GoogleDoc].

## Instructions

Reverse engineer the starter code provided and create a tutorial for the code.

In the Develop folder, there is starter code for a project. Begin inspecting the code to get an understanding of each file's responsibility. Then, in a Google Doc, write a tutorial explaining every file and its purpose. If one file is dependant on other files, be sure to let the user know.

At the end of the tutorial, add instructions for how you could now add changes to this project.

### Starter code:

```
.Develop
|
├── config
│   └── middleware
|    |  ├── isAuthenticated.js
|    ├── config.json
|    └── passport.js
│
├── models
│   └── index.js
|   └── user.js
│
├── public
│   └── js
|   |   ├────login.js
|   |   ├──── members.js
|   |   └──── signup.js
|   └── stylesheets
│       └── style.css
│
├── routes
|    ├── api-routes.js
|    └── html-routes.js
│
├── (node_modules)
├── (.gitignore)
├── (package-lock.json)
|
├── package.json
|
├── server.js
│

```

### User Story

```
AS A developer
I WANT a walk-through of the codebase
SO THAT I can use it as a starting point for a new prokect

```

### Acceptance Criteria

The application must meet the following requirements:

```
GIVEN a Node.js application using Sequelize and Passport
WHEN I follow the walkthrough
THEN I understand the codebase

```

### Business Context

When joining a new team, you will be expected to inspect a lot of code that you have never seen before. Rather than having a team member explain every line for you, you will dissect the code by yourself, saving any questions for a member of your team.

<!--1.
## Installation


2. Create a .gitignore file:

   - type `node_modules` in first line
   - type `.DS_Store` in second line

3. Create a new **package.json** file:

   - Initialize `npm`: `npm init`. This will be used to set up a new or existing npm package. You can customize the fields, or you can continue to press the enter key until you see `0 vulnerabilities`.
   - This will create a `package.json` file and a `package-lock.json` file.
   - Install the Inquirer package using: `npm install inquirer`
   - This will create a `node_modules` file.
   - You are now ready to create your `index.js` file: `touch server.js`

4. Set up Inquirer package within your newly created `server.js` file.

```
const inquirer = require('inquirer');
const fs = require("fs");
const util = require("util");
```

7. Copy and paste the code (or fork it) from the `server.js` within this repository.

8. Save file. Run `server.js` file within terminal using `node server.js`

9. If working, answer the prompts by entering your own inputs via the command line.
-->

### Definitions

The goals above and the tutorial can be further understood with the following definitions:

**database**
: a collection of data stored electronically.

**DBMS**
: the database management system (i.e. MySQL)

**MySQL**
: the most popular SQL database with a relational structure.

**SQL database**
: Structured Query Language.

**relational database**
: stores and finds data based on its relationship to other data in the database. Relational databases are tabular, meaning that data is stored in tables composed of rows and columns, much like a spreadsheet.

**MySQL command line prompt (MySQL Shell)**
: an advanced client and code editor for MySQL. Provides scripting capabilities for JavaScript and includes APIs for working with MySQL.

**CRUD**
: functions that Create Render Update Delete

**Primary Keys**
: aka primary keyword, a key in a relational database that is unique for each record; a unique identifier, such as a telephone number; a relational database must always have one and only one primary key.

**Foreign Keys**
: a column or group of columns in a relational database table that provides a link between data in two tables; acts as a cross-reference between tables because it references the primary key of another table, thereby establishing a link between them.

**Joins**
: command that joins two or more tables and the specified data and combines the data

**ACID**
: In database systems, (Atomicity, Consistency, Isolation, Durability) refers to a standard set of properties that guarantee database transactions are processed reliably; is concerned with how a database recovers from any failure that might occur while processing a transaction.

## Usage

![view](.png)

![view](.png)

## Credits

Reference articles:

## License

[MIT](MITLicense.txt)

---

© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
