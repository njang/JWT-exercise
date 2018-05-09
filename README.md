# JWT-exercise

## Resources
* How and when to use JSON Web Tokens for your services ([codecentric](https://blog.codecentric.de/en/2017/08/use-json-web-tokens-services/)): explains basic structure of the token as _header, payload and signature_.

* How to simplify your app’s authentication by using JSON Web Token ((Medium)[https://medium.freecodecamp.org/how-to-make-authentication-easier-with-json-web-token-cc15df3f2228])

* Securing Node.js RESTful APIs with JSON Web Tokens ([Medium](https://medium.freecodecamp.org/securing-node-js-restful-apis-with-json-web-tokens-9f811a92bb52))

* Using JSON Web Tokens (JWTs) ([Google Cloud Internet of Things Core](https://cloud.google.com/iot/docs/how-tos/credentials/jwts#iot-core-jwt-nodejs))

## Usage

```
npm install --save jsonwebtoken
npm install --save bcryptjs 
```
```
var jwt = require('jsonwebtoken');
var bcrypt = require('bcryptjs');
```
