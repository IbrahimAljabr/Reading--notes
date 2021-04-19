## Read 18

# AWS: API, Dynamo and Lambda


### What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and 
exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message 
producers or from being received by message consumers.

### How can the server be assured a message was properly received?
well recive a massage from the clinte side

### What classic design pattern is best represented by event driven programming?
Most of programming-languages comprise built-in “event” constructs implementing the observer-pattern components.

### How do you test an event driven system?
There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service 
tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a 
different part of your application.

## Term

### Serverless Functions
serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked 
through the Internet, are hosted and maintained by cloud computing companies.

### Cloud Storage

Cloud storage allows you to save data and files in an off-site location that you access either through the public internet or a dedicated 
private network connection. Data that you transfer off-site for storage becomes the responsibility of a third-party cloud provider.


### CDN
A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast 
delivery of Internet content. 

## Preparation Materials

### AWS API Gateway Overview
Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API 
and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, 
and tracing of API requests.

### AWS DynamoDB Guide
DynamoDB is a hosted NoSQL database offered by Amazon Web Services (AWS).

### Dynamoose
Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from 
Mongoose the syntax will be very familar.

