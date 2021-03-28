## Read 2

# Express

## Review, Research, and Discussion


### What’s the difference between PUT and PATCH?

- What is PUT?
PUT is a method of modifying resource where the client sends data that updates the entire resource. It is used to set an entity’s information completely. PUT is similar to POST in that it can create resources, but it does so when there is a defined URI. PUT overwrites the entire entity if it already exists, and creates a new resource if it doesn’t exist.

- What is PATCH?
Unlike PUT, PATCH applies a partial update to the resource.
This means that you are only required to send the data that you want to update, and it won’t affect or change anything else. So if you want to update the first name on a database, you will only be required to send the first parameter; the first name.

### Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

- [Mongodb](https://www.mongodb.com/)
- [Wiremock](http://wiremock.org/)
- [Stoplight](https://stoplight.io/mocking/)

### Compare and contrast Swagger and APIDoc.js 

The easiest way to understand the difference is:

    
    - Informational responses (100–199)
    - Successful responses (200–299)
    - Redirects (300–399)
    - Client errors (400–499)
    - Server errors (500–599)

### Compare and contrast SOAP and ReST

SOAP and REST both allow you to create your own API. API stands for Application Programming Interface. It makes it possible to transfer data from an application to other applications. An API receives requests and sends back responses through internet protocols such as HTTP, SMTP, and others.

**REST was created to address the problems of SOAP.**

SOAP is a standardized protocol that sends messages using other protocols such as HTTP and SMTP. The SOAP specifications are official web standards, maintained and developed by the World Wide Web Consortium (W3C). As opposed to SOAP, REST is not a protocol but an architectural style. The REST architecture lays down a set of guidelines you need to follow if you want to provide a RESTful web service, for example, stateless existence and the use of HTTP status codes.


### An introduction to NodeJS and Express

- node is an open-source, cross-platform runtime environment that allows developers to create all kinds of server-side tools and applications in JavaScript. 
- express is the most popular Node web framework, and is the underlying library for a number of other popular Node web frameworks

### NPM 
npm is the package manager for Node. js and the JavaScript coding language. It can be installed on a Linux system and then used on the command line to download and install JavaScript packages and their requisite dependencies

### TDD 
Test-driven development is a software development process relying on software requirements being converted to test cases before software is fully developed.

### CI/CD
In software engineering, CI/CD or CICD generally refers to the combined practices of continuous integration and either continuous delivery or continuous deployment. CI/CD bridges the gaps between development and operation activities and teams by enforcing automation in building, testing and deployment of applications







