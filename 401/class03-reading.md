# Class 3 Readings: Express REST API

### Name 3 real world use cases where you’d want to change the request with custom middleware

1. Authentication. You can write middleware that decodes a JSON webtoken and attaches a user property to the request, for use in later handlers
2. File handling. You may want to change the configuration of incoming files on the req object before they reach the main route
3. Documentation. You could use custom middleware to log or store information about any incoming request.

### True or false: The route handler is middleware?

True

### In what ways can a middleware function end the process and send data to the browser?

1. By calling next() and handing the req and res objects off to the next handler
2. By calling `next("with a message")` or with a `next(new Error("with a message"))`
3. By throwing an error

### At what point in the request lifecycle can you “inject” middleware?

After the request is recieved, before the response is sent

### What can cause express to error with “Request headers sent twice, cannot start a second response”

Sending a header in a middleware, then next()ing your req,res off to some other header that also wants to send a response

## Document the following Vocabulary Terms
#### Middleware
Functions that recieve (req,res,next) and do something with them before passing them off to the next handler.

#### Request Object
A fundamental part of the WRRC, the object that contains all the information about the incoming request to your server

#### Response Object
An object that is determined by the web server based on what route was accessed and what you want your server to do

#### Application Middleware
Middleware that is instantiated with App.use(someMiddleware). Every request that hits your app will go through this middleware

#### Routing Middleware
Middleware that is defined in the context of a single route ie `app.get("/home",authMW,(req,res)=>{});`

#### Test Driven Development
A style of development in which you write tests that define the desired behavior of your code before you write said code. Helps clarify code needs and avoid bugs

#### Behavioral Testing
Part of the interview process used to judge a candidates behavioral characteristics

## Preview
### Which 3 things had you heard about previously and now have better clarity on?
1. Javascript classes / prototype inheritance
2. Different ways of using an error handler
3. Using routing middleware

### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. API testing tools
2. TDD concepts
3. Express
### What are you most excited about trying to implement or see how it works?
1. Writing my own tests
2. Setting up the project structure
3. Doing cool stuff

