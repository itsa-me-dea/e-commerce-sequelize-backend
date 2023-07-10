# e-commerce-sequelize-backend

[![License Badge](https://img.shields.io/badge/license-MIT%20License-green?style=for-the-badge&logo=appveyor)](https://mit-license.org/)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=for-the-badge&logo=appveyor)](https://www.contributor-covenant.org/version/2/1/code_of_conduct/)

### **[Description](#description) | [Installation](#installation) | [Usage](#usage) | [Credits](#credits) | [License](#license) | [Contribute](#contribute) | [Tests](#tests) | [Questions](#questions)**

## Description

My motivation was to build the back end for an e-commerce site that creates and holds a database for retailers to utilize as a site for internet retailing / e-commerce. 

This creates a site that utilizes back-end features by configuring Express.js API to use Sequelize and interact with a MySQL database. ANd from this project, I learned how to utilize Sequelize and MySQL.

## Installation

Starting the Server:
1. Open a terminal with `server.js`
2. In the terminal, enter `npm install`
3. Update your `.env`
4. In the terminal, enter `mysql -u root -p` and complete
5. Enter `SOURCE db\schema.sql` and `exit`
6. Enter `npm run seed`
7. Enter `npm run start`
8. Open http://localhost:3001/ in Insomnia or related app

## Usage

This project will not be deployed. Refer to the following gifs and associated [tutorial video file](./Assets) or [tutorial video link](insert link).

<!-- 
The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)

Your walkthrough video should also show the POST, PUT, and DELETE routes for products and tags being tested in Insomnia.
 -->

## Credits

- Collaborators: 
  - N/A.
- Third-party assets: 
  - https://expressjs.com/
  - https://sequelize.org/
  - https://www.mysql.com/
- Tutorials: 
  - UCSD-VIRT-FSF-PT-03-2023-U-LOLC
  - https://medium.com/@sarahdherr/sequelizes-update-method-example-included-39dfed6821d
  - https://stackoverflow.com/questions/68926254/sequelize-using-where-in-include-in-findbypk
  - https://stackoverflow.com/questions/69836342/how-to-use-both-include-and-attributes-in-findbypk-statement-in-sequelize
  - https://stackoverflow.com/questions/50354817/sequelize-decimal-data-save-with-2-decimal-points



## License

 The license this application is covered under is: [MIT License](https://mit-license.org/).

## Contribute

In general, follow the "fork-and-pull" Git workflow.

  1. **Fork** the repo on GitHub.
  2. **Clone** the project to your own machine.
  3. **Commit** changes to your own branch.
  4. **Push** your work back up to your fork.
  5. Submit a **pull request** so that your changes can be reviewed.
    
  NOTE: Be sure to merge the latest from "upstream" before making a pull request!
  
  When contributing to this project, please follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) code of conduct.

## Tests

None.

## Questions

My gitHub username is [itsa-me-dea](https://github.com/itsa-me-dea), and you can contact me at wachadea@gmail.com.