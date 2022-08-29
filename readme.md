# GreenPet - Pet Care Store

<!-- <p>
    <img src="public/assets/img/wallpaper.png">
</p> -->

## Overview
The main purpose of this project is to create a webpage to a customer about her Pet Store.

<hr>

## Libraries 

- Bcrypt => Crypt password;
- Body-parser => Bypass json data;
- DotEnv => Work with envkeys;
- EJS => Render HTML;
- Express => Flexible framework;
- Express-session => create specific routes for admins controller;
- JWT: Json Web Token => Security Access 
- Nodemon => Update server when save;
- Sequelize => Manipulate database;
- Slugify => Replaces spaces with hyphen from saved text;
- TinyMCE => Manage blog hyper text

<hr>

## Set up `.env` file

- `DATABASE_USER` = root;
- `DATABASE_PASSWORD` = password
- `DATABASE_TABLE` = greenpet
- `DATABASE_HOST` = db

- `DATABASE_DIALECT` = postgres
- `SESSION_SECRET` = passwordSecret

- `POSTGRES_NAME` = greenpet
- `NEW_POSTGRES_NAME` = greenpet
- `POSTGRES_PASSWORD` = greenpet
- `POSTGRES_USER` = root
- `POSTGRES_DB` = greenpet

- `PORT` = 3000
- `DATABASE_TIMEZONE` = -03:00

- `JWT_TOKEN` = jwttoken

<hr>

## Running the application

To run the app you'll need [Docker](https://www.docker.com/products/docker-desktop/). After that, follow the steps below in your `terminal`:

- Run: `git` `clone` https://github.com/aleffaso/greenpet.git

- Run: `docker-compose up --build`

- Link: You can access the web page on `http://localhost:3000/`

- The application is also running at this [link](https://greenpet.herokuapp.com/) on Heroku

<hr>


## Licenses
<br>
<p>
    <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">
</p>
