## Installation

```bash
$ npm install
```

## Running the app

```bash
# create database -testDB
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Topics covered

- Database connection - postgres typeOrm
- local-auth - The local authentication strategy uses the email and password fields to authenticate users
- jwt-auth - JWT authentication strategy uses a JSON Web Token (JWT) to authenticate users
- refresh-jwt-auth - The refresh token is used to generate a new access token.
