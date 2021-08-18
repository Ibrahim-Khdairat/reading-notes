# Read 01 : Express

### 1- What’s the difference between PUT and PATCH?

The main difference between the PUT and PATCH method is that the PUT method use the request URI to supply a modified version of the requested resource which replaces the original version of the resource, where’s the PATCH method supplies a set of instructions to modify the resource.

### 2- Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

* [Postman](https://www.postman.com/) 
* [Mock Server](https://www.mock-server.com/)
* [Stoplight](https://stoplight.io/)

### 3- Compare and contrast SOAP and ReST : (Links to an external site.)
* REST versus SOAP. It’s been an issue for a while now. And really, they’re just two answers to the same question: how to access web services.

But deciding one over the other can be surprisingly difficult.

* SOAP (Simple Object Access Protocol) is a standards-based web services access protocol that has been around for a long time. Originally developed by Microsoft, SOAP isn’t as simple as the acronym would suggest

REST (Representational State Transfer) is another standard, made in response to SOAP’s shortcomings. It seeks to fix the problems with SOAP and provide a simpler method of accessing web services

### 4- Document the following Vocabulary Terms
##### 1- Web Server

A web server is the technology that serves up a website to users when they visit a URL. On the technical side of things, what that means is that it handles the hypertext transfer protocol (HTTP)

##### 2- Express

Web Applications Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.
##### 3- Routing

Routing is responsible for matching incoming HTTP requests and dispatching those requests to the app’s executable endpoints. Endpoints are the app’s units of executable request-handling code. Endpoints are defined in the app and configured when the app starts. The endpoint matching process can extract values from the request’s URL and provide those values for request processing. Using endpoint information from the app, routing is also able to generate URLs that map to endpoint