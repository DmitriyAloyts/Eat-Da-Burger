# Eat-Da-Burger
A burger logger with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). 
App is using MVC design pattern; use Node and MySQL to query and route data in app, and Handlebars to generate HTML.

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
Whenever a user submits a burger's name, app will display the burger on the left side of the page -- waiting to be devoured.
Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.
App will store every burger in a database, whether devoured or not.

#### Directory structure
All the recommended files and directories from the steps above should look like the following structure:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```
The app is deployed to Heroku