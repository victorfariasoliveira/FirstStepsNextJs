<h2 align="center">First steps with</h2>
<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>
  <p align="center">A progressive <a href="http://nodejs.org" target="blank">Node.js</a> framework for building efficient and scalable server-side applications, heavily inspired by <a href="https://angular.io" target="blank">Angular</a>.</p>
    <p align="center">

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```
## Routes

The api has some routes available, in this document you can find out what these routes are and a brief example of how to use them.

### Table of routes

The application routes are listed in the table below:

Rota  |  Descrição
--------------------  | --------------
`GET /cats/all`  | This route seeks all cats.
`GET /cats/:id`  | This route fetches the user with the id passed in the query params.
`POST /cats`  | This is a route to raise a cat.
`PUT /cats`  | This is a route to update a cat.
`DELETE /cats`  | This route fetches the user with the id passed in the parameters and deletes it.

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## License

  Nest is [MIT licensed](LICENSE).
