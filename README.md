# stock-shout [![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Questions](#questions)

## Description

This application is a back end for e-commerce website that
Uses the lastest technologies
So that their company can compete with other e-commer companies

This application can show, create, update, and delete products, categories and tags off of a server.

This application was created with express, mysql, and sequelize.

## Installation

The dependencies that this application uses are express, dotenv, mysql2, sequelize.

Ensure these are in you package.json upon cloning

Before opening a bash or mysql terminal, create an .env folder
containing a DB_USER, DB_PW, and a DB_NAME

```
==== GitBash ====
npm i [any missing dependencies]
mysql -u root -p

==== MySQL ====
Enter password: ******

source db/schema.sql (if you opened terminal from the root folder)
source schema.sql (if you opened terminal from from the db folder)

==== GitBash ====
node seeds/seed.js

npm start
```

## Usage

1. After running the program, open Insomnia
2. You can use Insomnia by using the urlss

```
localhost:3001/api/categories
localhost:3001/api/products
localhost:3001/api/tags
```

and using the get/post/put/delete commands

## Demo

[View Demo on Youtube]()

## Questions

If you have further questions you can email me at:
[njchin23@gmail.com](mailto:njchin23@gmail.com?subject=[GitHub%e%commerce%back%end])
