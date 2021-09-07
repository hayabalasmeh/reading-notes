# Our First Topic is about JSON Web Token

![jwt](https://cms-assets.tutsplus.com/uploads/users/1885/posts/30460/image/jwt-diagram.png)

## What is JSON Web Token?

- JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

- This information can be verified and trusted because it is digitally signed using a secret (with the HMAC algorithm) or a public/private key pair using RSA or ECDSA.

## When we should use JSON Web Tokens?

1- Authorization
2- Information Exchange

## What is the JSON Web Token structure?

- In its compact form, JSON Web Tokens consist of three parts separated by dots (.), 
- They are:

    - Header
    - Payload
    - Signature

- Therefore, a JWT typically looks like the following.

- **xxxxx.yyyyy.zzzzz**

## Why benefits of using JSON Web Tokens?

- As JSON is less verbose than XML, when it is encoded its size is also smaller, making JWT more compact than SAML.

- Security-wise, Signing XML with XML Digital Signature without introducing obscure security holes is very difficult when compared to the simplicity of signing JSON.

- JSON parsers are common in most programming languages because they map directly to objects

# Second Topic is How to Use JWT Authentication with Django REST Framework?

## How JWT Works?

- The JWT is acquired by exchanging an username + password for an access token and an refresh token.

- The access token is usually short-lived.

- The refresh token lives a little bit longer.

- It is comparable to an authentication session as after it expires, you need a full login with username + password again.

#### Obtain Token

1- First step is to authenticate and obtain the token

2- Store both the access token and the refresh token on the client side, usually in the localStorage.

3- In order to access the protected views on the backend you should include the access token in the header of all requests

#### Refresh Token

- To get a new access token, you should use the refresh token endpoint posting the refresh token.

- The return is a new access token that you should use in the subsequent requests.

- The refresh token is valid for the next 24 hours. 

- When it finally expires too, the user will need to perform a full authentication again using their username and password.

# Third Topic is about ,Django Runserver Is Not Your Production Server

- Running your app locally with **python manage.py** runserveris only for development 

- It’s very slow and it hasn’t been built with security concerns in mind.

## So what is good fit for production use?

- Use a **production-ready web server** like Nginx, and let your app be handled by a **WSGI application server** like Gunicorn.

