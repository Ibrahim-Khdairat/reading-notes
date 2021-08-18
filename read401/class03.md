# Read 03 : Express REST API

### 1- Name 3 real world use cases where you’d want to change the request with custom middleware

###### 1- Hight-level payment method security

###### 2- Track user behavior and stored

###### 3- Handling error

### 2. True or false: The route handler is middleware?
* ***False*** , they are not middleware functions by definition. If such function is used on routing methods then they are only handler functions. We use such a handler function which is not a middleware when it is the only one callback function.

Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next function is a function in the Express router which, when invoked, executes the middleware succeeding the current middleware.


### 3- In what ways can a middleware function end the process and send data to the browser?

Middleware functions that return a Promise will call next(value) when they reject or throw an error, next will be called with either the rejected value or the thrown Error.

### 4- At what point in the request lifecycle can you “inject” middleware? 
After the request have been received.

### 5- What can cause express to error with “Request headers sent twice, cannot start a second response"?
It usually happens when people treat an async response inside an express route as a synchronous response and they end up sending data twice.

### 6- Document the following Vocabulary Terms 
* **Middleware**: Middleware are different types of functions that are invoked by the Express.js routing layer before the final request handler. As the name specified, Middleware appears in the middle between an initial request and final intended route. In stack, middleware functions are always invoked in the order in which they are added.

* **Response Object**: e express.js request object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on. The following table specifies some of the properties associated with request object.

* **Application Middleware**: Middleware is software that lies between an operating system and the applications running on it. Essentially functioning as hidden translation layer, middleware enables communication and data management for distributed applications.

* **Routing Middleware**: middleware functions can perform the following tasks:Execute any code,Make changes to the request and the response objects.

* **Test Driven Development**:Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed,,

* **Behavioral Testing**:Behavioral testing is widely used and accepted as an integral part of toxicological evaluations. The data can be sensitive, specific, and reliable in detecting chemical effects, as well as useful for regulatory decisions and mechanistic evaluations in basic research. Interlaboratory comparisons indicate that data can be reliable and reproducible.