# expressjs-mongodb-auth
Authentication in ExpressJs with MongoDB using JWT

## Getting Started

### `npm install`
Installs all library on the package.json.

## Create your config.js file
```javascript
module.exports = {
    secret: 'your-secret-salt'
};
```

### `npm run dev` or `node index.js`
Runs the server on localhost:[port-number].

## Routes

### /
Method: get<br>
Header: authorization

### signup
Method: post<br>
Body: email and password

### signin
Method: post<br>
Body: email and password
