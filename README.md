# express-app-ejs-sequelize-boilerplate

## getting started

1. clone the repo

2. execute the following bash commands:

```bash
$ cd app
$ npm i
$ npm start
```

## boilerplate tasks completed

```bash
$ express --view=ejs --git app
$ cd app
$ npm i --save sequelize express-ejs-layouts dotenv
$ npm i --save-dev nodemon
$ npm i
$ sequelize init
$ mkdir routes/api
$ mkdir views/partials
$ touch views/layout.ejs
$ touch public/javascripts/main.js
$ touch .env .env.example
```

## developer notes

### to set up view engine:

```js
// view engine setup
app.set('views', path.join(__dirname, 'views'));
app.set('view engine', 'ejs');
```
