# Read 04 : Data Modeling

### 1- Name 3 advantages to Test Driven Development

###### 1- Better program design and higher code quality
###### 2- TDD reduces the time required for project development
###### 3- Detailed project documentation

### 2- In what case would you need to use beforeEach() or afterEach() in a test suite?
* If you have some work you need to do repeatedly for many tests, you can use beforeEach and afterEach.

`beforeEach()` is run before each test in a describe `afterEach()` is run after each test in a describe.

### 3- What is one downside of Test Driven Development

When feature changes, implementation will change as well, and many test cases will fail.
This problem exists as long as unit test exists, but more severe especially when the test cases are written during TDD. Since during TDD process people tend to focus on implementation, the test cases are more prone to change.

### 4- What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

**Classes** can’t be called without new, but **functions** intended as constructors can (and their this will be wrong) Classes can extend more types than constructors can (like functions and arrays) Classes prototypes are their parents (they inherit static properties); writers of constructor functions usually don’t bother with this.

### 5- Why REST?

its like creating knowledge of actions that happened before the client made the request and what will or should happen after the response is sent back to the client. REST is used when you are talking to your API.

### 6- Document the following Vocabulary Terms
* **Functional programming**: is the process of building software by composing pure functions, avoiding shared state, mutable data, and side-effects.

* **object-oriented programming (OOP)**: is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.

* **Class**: are a template for creating objects. They encapsulate data with code to work on that data.

* **super**: keyword to call the constructor of the super class.

* **this**: In the global execution context (outside of any function), this refers to the global object whether in strict mode or not.

* **Test Driven Development (TDD)**: is a software development process relying on software requirements being converted to test cases before software is fully developed.

* **Jest**: is a JavaScript testing framework developed by Facebook. It works out of the box with minimal configuration and has in-built test runner, assertion library and mocking support.

* **Continuous Integration (CI)**: is the practice of automating the integration of code changes from multiple contributors into a single software project.

* **REST**: is an architectural style that handles the client-server relationship

* **Data Model**: the process of visualizing and representing data for storage in a data warehouse. The model is a conceptual representation of the data, the relationships between data, and the rules. The modeling itself can include diagrams, symbols, or text to represent data and the way that it interrelates.