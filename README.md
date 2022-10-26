# E-Commerce Back End


  ## Description
  This project uses Node.js, Express.js, MySQL2, Sequelize, and DotEnv to create a server that hosts a database for an e-commerce operation. The data stored in this database can be accessed using API routes through express. These routes were tested using Insomnia.

  ## Table of Contents
  [Installation](#installation)

  [Usage](#usage)

  [License](#license)

  [Contributing](#contributing)

  [Tests](#tests)

  [Questions](#questions)

  ## Instillation
  To install this project and its dependencies, a user would first need to clone the GitHub repository, linked here:

  https://github.com/pmacdonald07/e-commerce-back-end.git

  Next, a user would need to open a terminal at the root of their directory and run the command "npm install". This would install the necessary dependencies.

  ## Usage
  In order to use this application, a user would need to update the dotenv file with their MySQL credentials. Then they would need to open a MySQL shell by running the command "mysql -u root -p" and enter their password when prompted.
  Next they would need to create the database by running the schema file with the command "source db/schema.sql". After the database has been successfully created, the user needs to quit the mysql shell and run the command "npm run seed", this will seed the database tables with products, categories, and tags.
  Lastly, to start the application itself, the user would run the command "npm start".

  A walkthrough video on using this application is linked below:
  
  https://drive.google.com/file/d/1rSz8BCiaBuZ7Xwc9PaQ0IPaXPNbrOY_r/view

  ## License
  There are no licenses associated with this project.

  ## Contributing
  Guidelines for contributing to this project:
  There are currently no guidelines for contributing to this project

  ## Tests
  A user can test the routes, database, and server by using Insomnia.

  ## Questions
  If you have any questions about the project, please reach out via the following:

  [Github Profile](https://github.com/pmacdonald07)

  patrickmacdonald07@gmail.com