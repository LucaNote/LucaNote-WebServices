# webservices-pieter-2122-LucaNote
<h1>Vastgoed API</h1>
This project was made during and after the course Web Services. In which we learned how to make a RESTful API.
<h2>Installation of API</h2>
To start the API, create a `.env` file in the root of this folder with this content

```
NODE_ENV="development"
DATABASE_USERNAME="root"
DATABASE_PASSWORD=""
```
Update the username and password with the credentials of your local database.

You can also extend the .env file with these configurations, only if the database host/port are different than our default.

```
DATABASE_HOST="localhost"
DATABASE_PORT=3306
```

<h2>How to start the API</h2>
Run the app in the terminal with `yarn start`.

<h2>Common Errors<h/2>

* Modules not found errors, try this and run again:

```
yarn install
```
