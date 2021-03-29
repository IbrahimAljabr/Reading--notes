## Read 3

# Express REST API


### Real world use cases for request with custom middleware :

- Handling error
- Data management
- Authentication



### True or false: The route handler is middleware? **false**

### In what ways can a middleware function end the process and send data to the browser?

- As name suggests it comes in middle of something and that is request and response cycle.
- Middleware has access to request and response object.
- Middleware has access to next function of request-response life cycle.

### At what point in the request lifecycle can you “inject” middleware?

- Between the request and the response 

### What can cause express to error with “Request headers sent twice, cannot start a second response”

- If it send more than one response


## Term

- Middleware : are functions that execute during the lifecycle of a request to the Express server.
- Request Object : The request object allows you to submit a POST or GET request to an URL. Essentially it provides a way to make REST API requests to another URL.
- Response Object : It is the object which communicates between the server and the output which is sent to the client.
- Application Middleware : application that use the middleware
- Routing Middleware : It is a piece of code that comes in the middle of request and response
- Test Driven Development : is a software development process relying on software requirements being converted to test cases before software is fully developed
- Behavioral Testing : A behavioural test investigates propensities towards certain kinds of behaviour and styles of interaction with others









