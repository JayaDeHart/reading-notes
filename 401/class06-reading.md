# Readings: Authentication

### Explain what a “Singleton” is (in Computer Science terms)
A code design pattern in which only one instance of class is allowed throughout the program. Generally, you would want the singleton class to be available globally throughout your application

### Explain how the Singleton pattern can be used with Node modules, specifically with classes
If you don't export the constructor for your class, no other files in the app can create another unwanted instance of your singleton

### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
I would probably create a system where you can move from one middleware to the next easily and also throw errors at any point in the system

## Document the following Vocabulary Terms
#### Router Middleware
Middleware that is specific to one route
#### Dynamic Module Loading
Loading modules only when they're required in order to improve performace
#### Singleton Pattern
A code design pattern in which only one instance of class is allowed throughout the program. Generally, you would want the singleton class to be available globally throughout your application
#### CRUD -> REST Method Matches
- CREATE -> POST
- READ -> GET
- UPDATE -> PUT/PATCH
- DESTROY -> DELETE

#### Mock Testing
When you simulate a particular environment or set of variables in order to test its functionality

### Which 3 things had you heard about previously and now have better clarity on?
1. Basic vs Bearer Authentication
2. Encoding vs Encryption
3. Salting vs Hashing
### Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. Oauth
2. User authorization
3. Hacking
### What are you most excited about trying to implement or see how it works?
1. Oauth
2. User authorization
