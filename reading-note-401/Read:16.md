## Read 16

# AWS: Cloud Servers

### What’s the difference between a FIFO and a standard queue?
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once 
processing.

### How can the server be assured a message was properly received?
by Message Authentication Code (MAC) is a tag attached to a message to ensure the integrity and authenticity of the message. It is derived 
by applying a MAC algorithm to a message in combination with a secret key.

### What classic design pattern is best represented by event driven programming?
Most of programming-languages comprise built-in “event” constructs implementing the observer-pattern components.

### How do you test an event driven system?
There are multiple levels of tests you will typically write for your system. In the most canonical case, you will 
write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is 
actually being tested) comprises a different part of your application.

## Term

### Server
In computing, a server is a piece of computer hardware or software that provides functionality for other programs or devices, called "clients".

### Pub/Sub
In software architecture, publish–subscribe is a messaging pattern where senders of messages, called publishers, do not program the messages to be sent directly 
to specific receivers, called subscribers

### WRRC
The web is a cycle of requests and responses that flow between clients and servers.

## Preparation Materials

### Virtual Machines 
to use more than operating system in the same computer

### VMS and the Cloud 
virtualization or virtualisation is the act of creating a virtual version of something, including virtual computer hardware platforms, 
storage devices, and computer network resources.

### AWS EC2
Amazon Elastic Compute Cloud is a part of Amazon.com's cloud-computing platform, Amazon Web Services, that allows users to rent virtual 
computers on which to run their own computer applications.

### Elastic Beanstalk
AWS Elastic Beanstalk is an orchestration service offered by Amazon Web Services for deploying applications which orchestrates various AWS 
services, including EC2, S3, Simple Notification Service, CloudWatch, autoscaling, and Elastic Load Balancers.
