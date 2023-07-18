# Stack Configuration Scripts

This repository contains scripts for configuring two different stacks: LAMP (Linux, Apache, MySQL, PHP) and MERN (MongoDB, Express.js, React, Node.js). These scripts automate the deployment process for each stack and provide a foundation for building web applications.

## LAMP Stack Configuration Script

The LAMP stack configuration script (`lamp-stack-config.sh`) enables the deployment of a simple ecommerce application built using PHP and MySQL. It automates the following tasks:

1. Installation and configuration of firewalld.
2. Installation and configuration of the MySQL database.
3. Addition of firewall rules for the database.
4. Creation of the necessary database and user.
5. Loading of inventory data into the database.
6. Installation of the Apache web server and PHP.
7. Addition of firewall rules for the web server.
8. Update of the Apache configuration file to set index.php as the default page.
9. Starting and enabling the Apache web server service.
10. Installation of Git.
11. Download of the ecommerce application code from Git.
12. Replacement of the database IP address with "localhost" in the index.php file.
13. Verification of the web server status and presence of required items on the webpage.

### Usage

To utilize the LAMP stack configuration script, follow these steps:

1. Clone the repository to your local machine:

   bash
   git clone https://github.com/your-username/repository.git
   

2. Navigate to the cloned repository:

   bash
   cd repository
   

3. Execute the LAMP stack configuration script:

   bash
   bash lamp-stack-config.sh
   

## MERN Stack Configuration Script

The MERN stack configuration script (`mern-stack-config.sh`) facilitates the deployment of a sample application built using MongoDB, Express.js, React, and Node.js. It automates the following tasks:

1. Installation and configuration of MongoDB.
2. Configuration of firewall rules for MongoDB.
3. Installation of Node.js and npm.
4. Cloning of the MERN stack application code from the specified Git repository.
5. Installation of project dependencies for both the client (React frontend) and the server (Express.js backend).
6. Building of the React frontend and relocation of the build folder to the server directory.
7. Starting the Node.js server.
8. Installation and configuration of Nginx as a reverse proxy.
9. Configuration of Nginx to serve the React app and proxy requests to the backend API.

### Usage

To utilize the MERN stack configuration script, follow these steps:

1. Clone the repository to your local machine:

   bash
   git clone https://github.com/your-username/repository.git
   

2. Navigate to the cloned repository:

   bash
   cd repository
   

3. Execute the MERN stack configuration script:

   bash
   bash mern-stack-config.sh
   

## License

These scripts are open-source and distributed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to modify and use them according to your needs.

## Disclaimer

These scripts are provided as-is without any warranty. Use them at your own risk.

Please ensure that you update the README file with the actual repository URL and script names before using it.
