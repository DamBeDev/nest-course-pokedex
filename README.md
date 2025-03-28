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
5. Rebuild database with seed
```
localhost:3000/api/seed
```

## Compile and run the project

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).
