# Authentication

## User Modeling

#### User models that have sensitive data that should NEVER be sent to client applications. If your application requires that users be able to read each others personal information, create a second Profile model to hold that data and strictly limit access to the Profile model. Safely using a second model will ensure that no users will accidentally (or maliciously) get access to sensitive information.
 
#### Should be encypted using a hashing algorithm before it is stored.

## Hash Algorithms

#### A Cryptographic Hash Algorithm takes a piece of data and produces a hash that is deliberately difficult to reverse. If identical data is passed into the algorithm the same hash will always be produced. Hash algorithms are often used for checking the integrity of data.

#### a hashed password can be stored when the user signs up and if the user needs to login, we can resesnd their password and the server can hash it using the same algorithm to compare it to the hashed password saved.

## Basic Auth

#### Basic Authorization is a common method used to send a username and password in an HTTP request. The username and password are joined with a ‘:’ then “base64 encoded” and placed after the string ‘Basic ‘. The resulting string is set to the value of an Authorization header.

