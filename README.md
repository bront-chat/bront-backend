# bront-backend
NodeJS backend for bront-chat

## Tech
Node.js - evented I/O for the backend  
Express - fast node.js network app framework  
Mongoose - elegant mongodb object modeling for node.js  
JWT Auth - JsonWebToken implementation for node.js  
Sengrid - Allows to quickly and easily send emails through SendGrid using nodejs.  
apiDoc - Inline Documentation for RESTful web APIs  
Mocha - simple, flexible, fun javascript test framework for node.js  

## Getting started
### Setup MongoDB on your local machine
Install [MongoDB](https://www.mongodb.com/download-center/community)

Start MongoDB server:
```
$ mongod --dbpath /usr/local/var/mongodb --logpath /usr/local/var/log/mongodb/mongo.log --fork
```

### Install NodeJS and dependencies and start node server
Install [Node.js](https://nodejs.org/) (version 8 is recommended).

```
$ cd bront-backend
$ npm install
$ node www/server
```

### Generating API Documentation
Running the following commands installs the `apidoc` CLI and generates documentation into the `/doc` directory
```
$ npm install -g apidoc
$ apidoc -i src
```