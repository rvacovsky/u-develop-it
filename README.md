# U Develop It

## Description

U Develop It is a command-line application for a local web developer meetup group to conduct voting for a new group president. Using a relational database (MySQL), data is stored and structured and is accessed through Express.js API.

## User Story

As a member of a web developer meetup group (U Develop It), I want a database that I populate and maintain with information about candidates, parties, and voters.

## Acceptance Criteria

When a user goes to the terminal and logs into MySQL, they can source the seed and schema files and start the 'election' database. With this information activated the user can then logout of MySQL and and start the node.js server. The user can use *Insomnia* (a REST API) to access established Express API routes to query the election database on a localhost. 

## Technologies Used

* [Express](https://expressjs.com/)
* [MySQL](https://www.mysql.com/)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Jest](https://jestjs.io/)
* [Insomnia](https://insomnia.rest/)
