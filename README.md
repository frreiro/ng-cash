<div align="center" >
  <img width="150px" src="https://notion-emojis.s3-us-west-2.amazonaws.com/prod/svg-twitter/1f4b0.svg" alt="ng-logo" width="400">
  <br>
  <br>
  <h1>NG Cash</h1>
</div>

## 📝 Description


NG.cash is a private web wallet application that allows users to, create an account and make transactions between themselves, this project is a challenge for a job at NG.CASH.


## 📦 Installation

Clone the repository.

```bash
# https
$ git clone https://github.com/frreiro/ng-cash
# ssh
$ git clone git@github.com:frreiro/ng-cash.git
```
## 🚀 Usage

### Docker mode

This repository use the two independent repositories and they need to be initialized with two commands: 

```bash
$ git submodule init
#and
$ git submodule update
```
Docker is configured to use your machine localhost as the container localhost. This option was choosed because the backend is not deployed yet, so this way was the pratice way to solve networking issues. Knowing that, just use those following command to start the application:

```bash
$ npm run docker:start
#or
$ yarn run docker:start
```

- Open `http://localhost:3000` in your brownser and see the magic appear


In case you want to stop the aplication run:
```bash
$ npm run docker:down
#or
$ yarn run docker:down
```

## 🔎 P.S.

Both repositories are independent, this repository are made to be a showase, where you can start the entire aplication easily using one docker command.
But if you want more details about frontend or backend and/or run a stack apart, check the following repositories.

 - [Backend](https://github.com/frreiro/ng-cash-backend)
 - [Frontend](https://github.com/frreiro/ng-cash-frontend)

## 📌 Features

- [x] User signup
- [x] User login
- [x] Create a user transfer
- [x] Read the user transactions
- [x] Read the user account information (balance, username)

## 🎨 Screenshots

<p align="center">
    <img height='400px' src="https://user-images.githubusercontent.com/98192816/203184773-ab7796fa-6713-4af2-b5fc-7d5235c27fff.png">
    <img height='400px'src="https://user-images.githubusercontent.com/98192816/203184926-119ddda9-043f-422c-9fa6-a6f45932bc01.png">
    <img height='400px'src="https://user-images.githubusercontent.com/98192816/203185090-b3358dea-dd7e-4dc7-8579-5ad9ad23cdef.png">
    <img height='400px'src="https://user-images.githubusercontent.com/98192816/203184942-a24e03a7-67d7-4e64-8472-d258d4b1f17a.png">
</p><br>


## 🚀 Technologies and Libraries
### Backend

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/)
- [eslint](https://eslint.org/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
- [Prisma ORM](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)

### Frontend

- [Next](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Styled-components](https://styled-components.com/)
- [Axios](https://axios-http.com/)
- [Dayjs](https://day.js.org/)
- [Reack-hook-form](https://react-hook-form.com/)
- [Joi](https://joi.dev/)
- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)
