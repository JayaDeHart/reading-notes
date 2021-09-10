

### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server
Both offer a set of routes/resources at a specific endpoint. Both contain specific 'route handers' that handle the server logic at each route. AWS API + Lambda is extremely modularized though. You save money by only firing the specific code you need to operate one route whenever that route is accessed.
### List the AWS Database offerings and talk about the pros and cons of each
Amazon DynamoDB and DocumentDB are noSQL databases that operate on the typical key:value structure. Amazon Aurora and RDS are SQL databases.
### What’s the difference between a FIFO and a standard queue?
"Standard queues provide at-least-once delivery, which means that each message is delivered at least once.

FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue"
-https://aws.amazon.com/sqs/faqs/


### How can the server be assured a message was properly received?
A read reciept
### Serverless API
Decentralizing the functions of a server into cloud hosted microservices
### Triggers
Things that cause something to happen
### Dynamo vs Mongo
Two different NoSQL DBMS
### Dynamoose vs Mongoose
Two javascript frameworks for interacting with these DMBSes

### Which 3 things had you heard about previously and now have better clarity on?
1. Lamda
2. API gateways
3. Dynamo DB
### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. Permissions / roles / IAM stuff
2. AWS
3. Servers
### What are you most excited about trying to implement or see how it works?
the lab
