
### How to run 

Book Store requires 
* [MongoDB](https://www.mongodb.com/download-center#community) v3.6+
* [NodeJS](https://nodejs.org/en/) v8+

To start the database (port: 27017): Install MongoDB, open new cmd window (in project root) and run

```sh
$ cd server
$ start-mongodb
```

To add initial seeding: (do this step once only the first time you start the app)
After you start MondoDB open new cmd window (in project root) and run

```sh
$ cd server
$ seedBooks
```

To start the server (port: 8000): open new cmd window (in project root) and run

```sh
$ cd server
$ npm install (if you havent already installed the dependencies)
$ npm start
```

To start the client (port: 4200): open new cmd window (in project root) and run

```sh
$ cd client
$ npm install (if you havent already installed the dependencies)
$ ng serve
```


### Author

[Nethma Aldeniya]

