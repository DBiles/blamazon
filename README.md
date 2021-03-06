# Blamazon

Small `Node` Application to display CLI operations with a MYSQL database.

## Prerequisites

Make sure you have [Node](https://nodejs.org/en/) installed. Once you have it installed you can check by running the following command:

```bash
node -v
```

For this application you will also need a version of [MYSQL](https://dev.mysql.com/downloads/mysql/). Once this is installed load the workbench and run the `schema.sql` file. This will create a new table that looks like this

![Database](./assets/images/database.png)

### Installing

Now that we have Node installed. Clone the repo and run the following command to download the dependencies needed for this application

```bash
npm install
```

## Running the application

Run the application use the following command and follow the prompts.

```node
node assets\js\blamazonCustomer.js
```

## Example

![Example](./assets/images/blamazondemo.gif)

## Built With

* [MYSQL](https://www.npmjs.com/package/mysqlw) - Connects with MYSQL
* [Inquirer](https://www.npmjs.com/package/inquirer) - Command Line Prompt

## Authors

* **Darron Biles** - [Me](https://github.com/DBiles)