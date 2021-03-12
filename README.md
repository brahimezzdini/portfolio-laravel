
## Laravel Portfolio

This project is a simple demonstration of a portfolio website using Laravel Framework. In this project the front-end is downloaded free from getbootstrap. However, I've worked specially on the back-end. The project is purely made for demonstration purpose and it is not for sale.



### Installation

You will need to be inside the project file to enter all of the rest of the commands. Type cd projectName to move to your terminal working location to the project file.

In this case: 

```be
cd Library_System
```
Install the dependencies and devDependencies and start the server.
You can also download the composer if not installed beforehand [here](https://getcomposer.org/)

```be
$ composer update
```

```be
$ npm install
```

```be
cp .env.example .env
```
```be
cp .env.example .env
```
```be
php artisan key:generate
```
In order to connect to the database:
 - Create a database
 - Locate to the database folder for a database file Vue_Laravel_MongoDB_Billing_Info\database\informations.json
 - Import the json file in the mongoDB database
 - In the .env file, fill out the DB_HOST, DB_PORT, DB_DATABASE, DB_USERNAME, and DB_PASSWORD options to match the credentials of the database.

Enter this to the command line :

```be
php artisan migrate
```
 
```be
php artisan serve

