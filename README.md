# [Web] GoRestaurant

## Table of Contents
* [Screenshots](#screenshots)
* [Installing](#installing)
  * [Configuring](#configuring)
    * [.env](#env)
    * [API](#api)
* [Usage](#usage)
* [Running the tests](#running-the-tests)
  * [Coverage Report](#coverage-report)

# Screenshots
Click to expand.<br>
<img src="https://raw.githubusercontent.com/GilsondaGama/GoStack11-Desafio-10-GoRestaurant-Web/master/screenshots/dashboard.png" width="32%"/>
<img src="https://raw.githubusercontent.com/GilsondaGama/GoStack11-Desafio-10-GoRestaurant-Web/master/screenshots/add-food.png" width="32%"/>
<img src="https://raw.githubusercontent.com/GilsondaGama/GoStack11-Desafio-10-GoRestaurant-Web/master/screenshots/edit-food.png" width="32%"/>

# Installing
Easy peasy lemon squeezy:
```
$ yarn
```
Or:
```
$ npm install
```
> Was installed and configured the [`eslint`](https://eslint.org/) and [`prettier`](https://prettier.io/) to keep the code clean and patterned.

## Configuring
Configure your environment variables and remember to start the [Json Server](https://github.com/typicode/json-server) API before to start this app.

### .env
In this file you may configure the API's url. Rename the `.env.example` in the root directory to `.env` then just update with your settings.

key|description|default
---|---|---
REACT_APP_API_URL|API's url|`http://localhost:3333`

### API
This application make usage of a third party library to create a fake API, you can see more information about it in [JSON Server](https://github.com/typicode/json-server) repository.

To start the API run:
```
$ yarn json-server server.json -p 3333
```
Or:
```
$ npx json-server server.json -p 3333
```
> Remember to update the `.env` if you choose another `port` or `host`

# Usage
To start the app run:
```
$ yarn start
```
Or:
```
npm run start
```

# Running the tests
[Jest](https://jestjs.io) was the choice to test the app, to run:
```
$ yarn test
```
Or:
```
$ npm run test
```

## Coverage Report
To generate/update the coverage report:
```
$ yarn coverage
```
Or:
```
$ npm run coverage
```
> You can see the coverage report inside `tests/coverage`.
