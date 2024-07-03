# MERN Ecommerce

## Description

An ecommerce store built with the MERN stack that utilizes third-party APIs. This ecommerce store enables three main different flows or implementations:

1. Buyers browse the store categories, products, and brands.
2. Sellers or Merchants manage their own brand component.
3. Admins manage and control the entire store components.

### Features
- **Node.js** provides the backend environment for this application.
- **Express** middleware is used to handle requests and routes.
- **Mongoose** schemas model the application data.
- **React** is used for displaying UI components.
- **Redux** manages the application's state.
- **Redux Thunk** middleware handles asynchronous Redux actions.

## Quickstart Guide

To run this project locally, you can use the Docker Compose provided in the repository. Here is a guide on how to run this project locally using Docker Compose:

1. Clone the repository:
    ```sh
    $ git clone https://github.com/Anmol0809/QuadB-Tech.git
    ```

2. Edit the `docker-compose.yml` file and update the values for `MONGO_URI` and `JWT_SECRET`.

3. Start Docker Compose:
    ```sh
    $ docker-compose -f docker-compose.yml up
    ```

## Database Seed

- The seed command will create an admin user in the database.
- The email and password are passed with the command as arguments.
- Use the following command (replace brackets with email and password):
    ```sh
    npm run seed:db [email@example.com] [password]
    ```
- For more information, see code [here](server/utils/seed.js).

## Demo

This application is deployed on Vercel. Please check it out 😊 [here](https://mern-store-gold.vercel.app).

See the admin dashboard [demo](https://mernstore-bucket.s3.us-east-2.amazonaws.com/admin.mp4).

## Install

Some basic Git commands are:
```sh
$ git clone https://github.com/Anmol0809/QuadB-Tech.git
$ cd project
$ npm install
```

## Start Development

```sh
$ npm run dev
```

## Simple Build for Production

```sh
$ npm run build
```

## Run Build for Production

```sh
$ npm start
```

## Languages & Tools

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Mongoose](https://mongoosejs.com/)
- [React](https://reactjs.org/)
- [Webpack](https://webpack.js.org/)

### Code Formatter

- Add a `.vscode` directory.
- Create a file `settings.json` inside `.vscode`.
- Install Prettier - Code formatter in VSCode.
- Add the following snippet:

    ```json
    {
      "editor.formatOnSave": true,
      "prettier.singleQuote": true,
      "prettier.arrowParens": "avoid",
      "prettier.jsxSingleQuote": true,
      "prettier.trailingComma": "none",
      "javascript.preferences.quoteStyle": "single"
    }
    ```