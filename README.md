# Freelancer Web Site

It is a website designed using Express JS. Although it is a single page application, we have completed the necessary fields for the administrator via modal.

The portfolio section in the application is dynamic and the other sections have a static structure.

A ready theme was used for the application development. Start Bootstrap -

## Installation

You can fork the application or download the files to your computer. When you download the application to a folder on your computer.

- Open the command line and go to the directory where your project is via the command line.
- Prepare the application to start with the ```npm init``` command.
- Fill in the **APP_MONGODB_DB_NAME=database_name**, **APP_MONGODB_FULL_URL=database_full_url** and **APP_SESSION_SECRET_KEY=** fields in the **.env** file.
- Run your application with the ```node app``` command.

An example **.env** file can be like this.

```
PORT=5000
APP_MONGODB_DB_NAME=db-freelancer
APP_MONGODB_FULL_URL=mongodb://localhost:27017
APP_SESSION_SECRET_KEY=EkdsOpaaufaaa222UfaaaUUP
```

Here you can set the database name according to yourself. You can also add the full MongoDB URL, if there is a password and username, and if you have a test server on your own computer, you can use it directly as above.

APP_SESSION_SECRET_KEY is a randomly generated string.

If you did all the operations correctly, your server will start working after the ```node app``` command. Now you can access the web page from the address ```http://localhost:5000```. For the first use, you can set up an administrator from ```http://localhost:5000/login```. Only one administrator / user is allowed. Afterwards, you can log in from ```http://localhost:5000/login``` and enter the necessary images and information in the portfolio section by clicking on the **ADD** link.

## Technologies Used

The application is developed based on Node JS. The packages used are listed below.

- Express JS
- Bootstrap
- Mongodb
- express-session
- express-fileupload
- express-validator
- randomstring
- mongoose
- bcrypt
- dotenv
- ejs
