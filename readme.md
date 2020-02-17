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

### Sending Request

You can sent POST request usiing Postman.

#### Articles Details

<table>
    <thead>
      <tr>
        <th>Method</th>
        <th>URL</th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>GET</td>
            <td>/articles</td>
        </tr>
    </tbody>
  </table>

Response

Using pagination to list just five data.

    {
        "data": [
            {
                "id": 34,
                "title": "Odio et eos ea soluta eum.",
                "body": "Ut non facilis aperiam quia. Nam est vero reiciendis facere asperiores ipsam consequatur. Minus eius ut ipsum sit."
            },
            {
                "id": 33,
                "title": "Nostrum beatae earum error optio temporibus.",
                "body": "Aliquid sed laboriosam qui aut minima eaque. Possimus sed vero doloremque qui culpa ullam."
            },
            {
                "id": 31,
                "title": "Test Tile",
                "body": "TestBody"
            },
            {
                "id": 1,
                "title": "Nostrum beatae earum error optio temporibus.",
                "body": "Aliquid sed laboriosam qui aut minima eaque. Possimus sed vero doloremque qui culpa ullam."
            },
            {
                "id": 3,
                "title": "Odio et eos ea soluta eum.",
                "body": "Ut non facilis aperiam quia. Nam est vero reiciendis facere asperiores ipsam consequatur. Minus eius ut ipsum sit."
            }
        ],
        "links": {
            "first": "http://127.0.0.1:8000/api/articles?page=1",
            "last": "http://127.0.0.1:8000/api/articles?page=7",
            "prev": null,
            "next": "http://127.0.0.1:8000/api/articles?page=2"
        },
        "meta": {
            "current_page": 1,
            "from": 1,
            "last_page": 7,
            "path": "http://127.0.0.1:8000/api/articles",
            "per_page": 5,
            "to": 5,
            "total": 32
        }
    }


<hr></hr>