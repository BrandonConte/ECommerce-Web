<p align="center">
  <a href="https://github.com/BrandonConte/ECommerce-Web" rel="noopener"></a>

</p>


<h3 align="center">Full E-Commerce Web</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/BrandonConte/ECommerce-Web.svg)](https://github.com/BrandonConte/ECommerce-Web/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/BrandonConte/ECommerce-Web.svg)](https://github.com/BrandonConte/ECommerce-Web/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Complete and fully functioning back-end database.
    <br> 
</p>


## <img src="./themes/clean-dark/menu-categories/table-of-context.png" style="height: 40px">

- [About](#about)
- [Installing](#installing)
- [Usage](#usage)
- [Built With](#built_using)
- [Authors](#authors)
- [Questions](#questions)

## <img id="about" src="./themes/clean-dark/menu-categories/about.png" style="height: 40px">
[Video Demo](////////INSERT LINK HERE///////)
Unfortunately I was unable to record this functioning

This repository is where I develop a back-end database using Sequelize and ORM concepts to implement with any e-commerce front-end.

## <img id="installing" src="./themes/clean-dark/menu-categories/installing.png" style="height: 40px">

Once you have cloned the repo down from GitHub, you will want to run `npm install` in the command line to install all of the Node Modules needed to run the application.

## <img id="usage" src="./themes/clean-dark/menu-categories/usage.png" style="height: 40px">

In order to run this program locally you will need to:

1. Clone this repository to receive all the files.
2. Run `npm install` in the terminal to download all the needed dependencies (makes sure you are in the correct file directory).
3. Create a `.env` file and input the followings keys: `DB_NAME='ecommerce_db' DB_USER='your user' DB_PW='your password'` Where the values for `DB_USER` AND `DB_PW` are your MySQL credentials
4. Run `source db/schema.sql` in your MySQL command line interface to initialize the database
5. (OPTIONAL) Run `npm run seed` to initialize seeding scripts to insert test data into the database
6. Run `npm start` in the terminal to start a live server locally.
7. Use any preferred application to call API routes defined within JavaScript files in the routes directory.

## <img id="built_using" src="./themes/clean-dark/menu-categories/built-using.png" style="height: 40px">

- JavaScript
- Sequelize
- MySQL
- Express.js
- Node.js

## <img id="authors" src="./themes/clean-dark/menu-categories/authors.png" style="height: 40px">

- [@BrandonConte](https://github.com/BrandonConte)
- See also the list of [contributors](https://github.com/coding-boot-camp/fantastic-umbrella/graphs/contributors) who participated in this project.


## <img id="questions" src="./themes/clean-dark/menu-categories/questions-alt.png" style="height: 40px">

- Feel free to open an issue or contact me directly at contact@brandonconte.com if you have any questions about the repo. You can find more of my work at [BrandonConte](https://github.com/BrandonConte/).

## License

Copyright (c) Microsoft Corporation. All rights reserved.