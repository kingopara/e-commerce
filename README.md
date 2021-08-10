# e-commerce

## Description

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Table of content
* [links to walkthrough video](#video)
* [Project Requirements](#projectrequirements)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)
* [Badges](#Badges)
* [Contributing](#contributing)

## Links to walkthrough video

[link to a walk-through video of how the app works](https://drive.google.com/file/d/1O6vy--c8fZmiECuKYJVcC-QfwJ308taR/view?usp=sharing)

[link to a walk-through video of how the app works](https://youtu.be/Fd8-HntRUXc)

## Project Requirements

*    WHEN I add my database name, MySQL username, and MySQL password to an environment variable file,
    THEN I am able to connect to a database using Sequelize

*    WHEN I enter schema and seed commands,
    THEN a development database is created and is seeded with test data

*    WHEN I enter the command to invoke the application
    THEN my server is started and the Sequelize models are synced to the MySQL database

*    WHEN I open API GET routes in Insomnia Core for categories, products, or tags
    THEN the data for each of these routes is displayed in a formatted JSON

*    WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
    THEN I am able to successfully create, update, and delete data in my database


## Installation

Install packages to use the app

npm init

npm install sequelize

npm install mysql2

npm install dotenv

npm install express

## Usage 

At the root of the directory, run these commands:

* mysql -u root -p (to log into mysql shell & enter your password)
* source db/schema.sql (to create the schema)
* npm run seed (to seed the database from the command line)
* npm start or node server.js (to start the application's server)

## Credit
This app was made with love and hardwork by Praise Opara

## License

[MIT](https://opensource.org/licenses/MIT)

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

## Contributing

![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)]