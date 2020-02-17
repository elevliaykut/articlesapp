<hr></hr>

### Article Application

<hr></hr>

This is a sample REST API application uses laravel and Vue.js. It allows you POST,GET,PUT,DELETE request to manage articles.

<hr></hr>

Technologies used;

✔️ Laravel 5.5.48 as framewaork

✔️ Composer for dependency management

✔️ Mysql 5.7.12 for database management

✔️ Restful Web Services

✔️ Vue.js with FrontEnd

<hr></hr>

<img src="./images/article.png" width="100%" height="400"/>

<hr></hr>

### Installation

- Clone the repository and go to project directory.

        git clone https://github.com/elevliaykut/articlesapp.git

        cd articlesapp

- Rename .env.example to .env

- Connect to MySQL and create a database.

        mysql -u root -p

        create database 'larticles'

- Update the .env file with database connection details.

        DB_DATABASE=larticles
        DB_USERNAME=username
        DB_PASSWORD=password

- After setting the environment, run the build.sh

- Install package manager to Vue.js

        npm install

        npm run watch

and you're all done! You have startted the server on http://127.0.0.1:3000/

<hr></hr>