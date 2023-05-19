# Employee Generator

![License](https://img.shields.io/static/v1?label=license&message=MIT&color=brightgreen)

## Description

This is a back end for an e-commerce site. Express.js API was configured to use Sequelize to interact with a MySQL database

## Table of Contents

* [Walkthrough Video](#Walkthrough-Video)    
* [Installation](#Installation)  
* [Usage](#Usage)   
* [License](#License)  
* [Tests](#Tests)  
* [Questions](#Questions)

## Walkthrough-Video

Watch this [video](https://drive.google.com/) demonstration to learn the functionality and how to use the application.

## Installation 

1. Clone the [repository](https://github.com/Garethus/e-commerce-back-end) of this project from Github into your local machine. 
2. Navigate to the project's directory. 
3. Then, run `npm install` to install the npm package dependencies. 
4. Rename .env.EXAMPLE file to .env and update DB_USER and DB_PASSWORD with your MySQL account.
5. Create the database by execute the `db/schema.sql` file in MySQL Shell.
6. Run `npm run seed` to seed the database.
7. Run `npm start` to initiate the server.

## Usage

Run the server and use Insomia or Postman to interact with the different endpoints of the database.
Use API GET routes to return categories, products, and tags either all or single.
Use API POST, PUT, and DELETE routes to create, update, and delete data in the database.

[Example of GET request to return all products](./images/getall.JPG)
[Example of GET request to return a single product](./images/getsingle.JPG)
[Example of POST request to CREATE Category](./images/post.JPG)
[Example of PUT request to UPDATE Category](./images/put.JPG)
[Example of DEL request to DELETE Category by ID](./images/delete.JPG)

## License

Licensed under the [MIT](./LICENSE) license.

## Contributing

If you want to help me make this application better, clone the repo, commit your changes and create a pull request. Thanks!

## Tests

No test for this application.

## Questions
    
If you have any questions about the project please contact me through my [GitHub](https://github.com/Garethus) or email me at reyes.grethelmaec@gmail.com.

