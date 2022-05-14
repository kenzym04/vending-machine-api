# Vending Machine API

## Description

Design an API for a vending machine, allowing users with a “seller” role to add, update or remove products, while users with a “buyer” role can deposit coins into the machine and make purchases. Your vending machine should only accept 5, 10, 20, 50 and 100 cent coins.

## Set up

```bash
$ git clone https://github.com/kenzym04/vending-machine-api.git
$ cd vending-machine-api
$ cp .env.example #Update the the file with your DB credentials
$ yarn or npm install
```

## Run

```bash
# development
$ yarn start or npm run start

# watch mode
$ yarn start:dev or npm run start:dev

# production mode
$ yarn start:prod or npm run start:prod
```

## Test

```bash
# unit tests
$ yarn test or npm run test

# test coverage
$ yarn test: cov or npm run test:cov

# e2e tests
$ yarn test:e2e or npm run test:e2e
```

## Documentation

Input this url  ```http://localhost:1003/docs``` on your server's browser to view the api documentation.

## Stack

* **Runtime Environment**: [NodeJS](https://nodejs.org/en/)
* **Language**: [Typescript](https://www.typescriptlang.org/)
* **Web Framework**: [NestJS](https://docs.nestjs.com)
* **Database**: [Mysql](https://www.mysql.com/)
