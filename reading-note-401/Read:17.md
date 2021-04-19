## Read 17

# AWS: S3 and Lambda

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

### Server Instances
An instance is a single copy of the software running on a single physical or virtual server. If you run two copies of the 
software on the same physical or virtual server, that counts as two instances.

### Containers
Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers.

### Cloud Services
Cloud computing is the on-demand availability of computer system resources, especially data storage and computing power, without 
direct active management by the user. The term is generally used to describe data centers available to many users over the Internet

### Cloud Architecture
Cloud Architecture refers to the various components in terms of databases, software capabilities, applications, etc.

### AWS
Amazon Web Services is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments

### EC2/Beanstalk vs Heroku
In short, Heroku vs AWS means Heroku vs Elastic Beanstalk. ... We deploy applications on AWS Elastic Beanstalk by running commands in a 
Command Line Interface (provided by AWS) or by using the Management Console. After deployment, Elastic Beanstalk manages infrastructure 
without our control.

## Preparation Materials

### AWS S3
Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, 
security, and performance. This means customers of all sizes and industries can use it to store and protect 

### AWS Lambda Basics
AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, 
self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes 
those functions in an efficient and flexible manner.

### AWS Lambda Functions
AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers, creating workload-aware 
cluster scaling logic, maintaining event integrations, or managing runtimes. 

### CDN
A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast 
delivery of Internet content. 

