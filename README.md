# E-commerce Back End Starter Code

## Table of Contents
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Licenses](#license)
  * [Contributing](#contributing)
  * [Credits](#credits)
    
## Description
This is a simple back end application using ORM. This application uses GET, PUT, POST, and DELETE routes to interact with database changes. Please have insomnia ready.

## Installation
Please do an `npm i` prior to running the script.
Or individual packages:
`npm install dotenv`
`npm install express`
`npm install mysql2`
`npm install sequelize`
Recent version of inquirer will not work with this tool.

Please also update your own mysql password into the connection.js using a .env file. And in terminal run `mysql -u root -p`, enter your password, `SOURCE db/schema.sql` exit and `npm run seed` to get the database started.

Lastly, run `node server.js` and open server on insomnia.

## Usage
Sample video link: https://drive.google.com/file/d/17ozFUBXlmbimP-5RvDm8EwDzmblFSgxu/view

![insomnia walkthrough GIF](./images/M13-ORMChallenge.gif)

## License
MIT License

## Contributing
Feel free to clone or fork the repo and create any changes you wish to make the application better!

## Credits
Original code source: https://github.com/coding-boot-camp/fantastic-umbrella
