# Class 2 Readings: Express

## What’s the difference between PUT and PATCH?

Put replaces the resource its editing, while Patch modifies.

## Provide links to 3 services or tools that allow you to “mock” an API for development like

1. [Postman](https://www.postman.com/)
2. [HttPie](https://httpie.io/)
3. [Mirage](https://miragejs.com/)

## Compare and contrast Swagger and APIDoc.js 1. Which HTTP status codes should be sent with each type of (un)successful API call?
  
  From the [Swagger Docs](https://swagger.io/docs/specification/describing-responses/)
  
  ```
  responses:
        '200':
          description: OK
        '400':
          description: Bad request. User ID must be an integer and larger than 0.
        '401':
          description: Authorization information is missing or invalid.
        '404':
          description: A user with the specified ID was not found.
        '5XX':
          description: Unexpected error.
   ```
   
  ## Compare and contrast SOAP and ReST
   
   - Both are methods of transferring data through the internet
   - Soap relies on XML
   - REST uses the HTTP verbs GET POST PUT DELETE

  ## Document the following Vocabulary Terms
  
  #### Web Server
  
  A combination of hardware and software that can accept and send HTTP requests
  
  #### Express
  
  A Javascript library that simplifies the process of creating a node.js web server
  
  #### Routing
  
  Creating endpoints on your web server, deciding what methods are needed to reach them and assigning functionalities to those routes
  
  #### WRRC
  
 The "Web Request Response Cycle"
 
### Which 3 things had you heard about previously and now have better clarity on?
- Express
- Jest
- CI/CD

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- Error first callback system
- Error handling middleware
- Testing middleware

### What are you most excited about trying to implement or see how it works?
- Writing my own jest tests
- Testing middleware
- Writing custom error handling middleware
