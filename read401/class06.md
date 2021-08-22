# READ 06 :  Authentication

### Explain what a “Singleton” is (in Computer Science terms) ?
* A singleton is a class that allows only a single instance of itself to be created and gives access to that created instance.
* It is used in scenarios when a user wants to restrict instantiation of a class to only one object.

### Explain how the Singleton pattern can be used with Node modules, specifically with classes ?
* The singleton pattern is used in programming languages such as Java and .NET to define a global variable. A single object used across systems remains constant and needs to be defined only once rather than many times.
* After we instantiate once, every time we call to instantiate again, it will not create another instance.. instead it will refer to only one instantiation (the first one).

### Document the following Vocabulary Terms (Links to an external site.)
* **Router Middleware**:
to set a class before we enter the route. components/Navigation.vue changes the font size for the route with the name of router-middleware. nuxt.config.js contains the router property to activate the middleware.

* **Dynamic Module Loading**: 
A recent addition to JavaScript modules functionality is dynamic module loading. This allows you to dynamically load modules only when they are needed, rather than having to load everything up front. This has some obvious performance advantages; let’s read on and see how it works.

* **Singleton Pattern** :
is a creational design pattern that lets you ensure that a class has only one instance, while providing a global access point to this instance.

* **CRUD -> REST Method Matches** : 
In RESTful style programming, we should use HTTP methods as our building blocks. I’m a little confused though which methods match up to the classic CRUD methods. GET/Read and DELETE/Delete are obvious enough.

* **Mock Testing** :
Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. In mock testing, the dependencies are replaced with objects that simulate the behaviour of the real ones.

