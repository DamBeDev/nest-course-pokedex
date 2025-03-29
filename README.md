<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Run in development

1. Clone the repository

2. Execute
```bash
$ npm install
```

3. Have Nest CLI installed
```bash
$ npm i -g @nestjs/cli
```

4. Get up the database
```bash
$ docker-compose up -d
```

5. Clone file ```.env.template``` and rename to ```.env```

6. Complete defined environment variables in ```.env```

7. Compile and run the project in watch mode
```bash
$ npm run start:dev
```

8. Rebuild database with seed
```
localhost:3000/api/seed
```

## Compile and run commands

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Stack
* MongoDB
* Nest
* Docker

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
