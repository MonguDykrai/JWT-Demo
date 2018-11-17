# README

package.json

```
{
  "name": "08_JWT",
  "version": "1.0.0",
  "description": "JWT example",
  "main": "app.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC"
}
```

npm install express jsonwebtoken

npm install -g nodemon

/api

![](./images/index.png)

/api/posts

![](./images/posts.png)

/api/login

![](./images/login.png)

verifyToken

![](./images/verifyToken.png)

带 authorization

![](./images/authorization.png)

无 authorization

![](./images/without_authorization.png)

不对称

![](./images/authorization_unsymmetric.png)

未过期

![](./images/expiresIn_1.png)

过期

![](./images/expiresIn_2.png)

JWT

![](./images/JWT.png)

JWT Signature Verify

![](./images/JWT_Signature_Verify.gif)

JWT 会引起 SIGNATURE 发生改变的因素 HEADER、PAYLOAD、密钥

![](./images/会引起_SIGNATURE_发生改变的因素_HEADER_PAYLOAD_密钥.gif)

JWT Header、Loader、Signature 详细说明

![](./images/JWT_三个部分的详细说明.png)

## secret base64 encode

I don't what you're trying to achieve here... base64 encoded keys are usually used when they are not plain strings (like binary content).

![](./images/secret_base64_encode.gif)

secret base64 encode
<https://github.com/lcobucci/jwt/issues/217>