# Reading 19

## AWS Events

### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

They are all used in the WRRC.They are just different ways of sending the response

### List the AWS Database offerings and talk about the pros and cons of each

Amazon RDS - relational databases
Amazon DynamoDB - serverless NoSQL databases
Amazon Redshift - data warehouse
Amazon Elesticache - in-memory data store
Amazon Document DB - MongoDB

### What’s the difference between a FIFO and a standard queue?

FIFO is garounteed to always be first in-first out

### How can the server be assured a message was properly received?

by responding with a message or status code describing whether or not the message was received.

### Terms

- Serverless API: An API that runs on cloud triggers instead of an expressJS server.

- Triggers: conditions that cause a piece of code to run

- Dynamo vs Mongo: Dynamo is limited to AWS wheras Mongo is platform-agnostic

- Dynamoose vs Mongoose: These are the ORM libraries for their respective databases.
