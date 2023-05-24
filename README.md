## Installation 

1: clone the repository

2: go to the project directory

3: run the command npm install


## Running the app

```bash
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
## .env file structure  

```bash
DB_HOST=localhost
DB_PORT=5432
DB_USER=postgres
DB_PASS="password"
DB_DIALECT=postgres
DB_NAME_TEST="TEST Database Name"
DB_NAME_DEVELOPMENT="DEVELOPMENT Database Name"
DB_NAME_PRODUCTION="PRODUCTION Database Name "
JWTKEY="secret key "
TOKEN_EXPIRATION=48h
BEARER=Bearer
```
