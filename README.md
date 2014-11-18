# dataJS
A lightweight data access layer for MySQL

## Usage
```javascript
var mysql = require('mysql');
var config =  {
               host: ...,
               user: ...,
               password: ...,
               database: ...
              };

var connection = mysql.createConnection(config);
```

## Dependencies
```
npm install mysql
```
