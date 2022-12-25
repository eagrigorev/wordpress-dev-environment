# WordPress Development Environment

## Information

Fork that repository and start developing your own WordPress themes and plugins. Based on Brad Traversy tutorial. This repository includes some basic JavaScript styling through ESLint and Prettier extensions.

## Setup

1. Fork that repository and download it using HTTPS or SSH connection
2. Run ```npm install``` to set up node modules
3. Rename ```.env-example``` into ```.env``` and replace generic passwords and usernames with your desired values
4. Install Docker and run ```docker-compose up -d```
5. Depending on what you are going to develop, adjust ```.gitignore``` accordingly

## Usage

Access WordPress installation via ```localhost``` and use your ```.env``` credentials to install CMS. WordPress files will be copied into the ```wordpress/``` directory. Work right in the ```wp-content/themes``` and ```wp-content/plugins``` directories. To access the database, go to ```localhost:8080```.