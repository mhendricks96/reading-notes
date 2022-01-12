# Express

## What is the difference between Put and Patch?

- In PUT the client says something that will modify the entire resource. If it does not exist already, it will be created.
it will ALWAYS replace what exists with what you send it, so if you send less than already exists, you will lose what you didnt send.

- PATCH however can do partial updates. so if you send less than exists, it will only change what you send and will leave the rest untouched.

## Mock API services

- [postman](https://www.postman.com/)

- [insomnia](https://insomnia.rest/)

- [thunder client](https://www.thunderclient.io/)

## Swagger visits APIDoc

- swagger is open source and uses vanilla js.

## REST vs SOAP

- SOAP (Simple Object Access Protocol) was created first so many lagacy systems use it. SOAP is a protocol with specific requirements like XML messaging.

- REST (Representational State Transfer) is a faster alternative in web-based scenarios. Many public

## Terms

### Express

- a node framework

- Write handlers for requests with different HTTP verbs at different URL paths (routes).

- can integrate with "view" rendering engines in order to generate responses by inserting data into templates.

- can set common web application settings like the port to use for connecting, and the location of templates that are used for rendering the response.

- can add additional request processing "middleware" at any point within the request handling pipeline.

### web server

- software that uses the Hypertext Transfer Protocol, commonly known as HTTP, and some other protocols that respond to request from clients

### routing

- Routing refers to how an application's endpoints (URIs) respond to client requests.

### WRRC

- The Web Request Response Cycle is the process a client goes through when asking a server for data.
