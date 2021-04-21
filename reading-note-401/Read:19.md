## Read 19

# AWS: Events

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

### Serverless API
Serverless is a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers.

### Triggers
A database trigger is procedural code that is automatically executed in response to certain events on a particular table or view in a database. 

### Dynamo vs Mongo
DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas. ... DynamoDB uses tables, 
items and attributes, MongoDB uses JSON-like documents. DynamoDB supports limited data types and smaller item sizes; MongoDB supports 
more data types and has fewer size restrictions.

### Dynamoose vs Mongoose
- Dynamoose is a modeling tool for Amazon's DynamoDB (inspired by Mongoose).
- Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in 
type casting, validation, query building, business

### SQS and SNS Basics
- Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, 
  distributed systems, and serverless applications
- Amazon SNS is a fully managed service, taking care of the heavy lifting related to capacity planning, provisioning, monitoring, and patching.

