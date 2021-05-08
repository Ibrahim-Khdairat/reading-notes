# Read: 10 - JS Debugging

## Ch. 10, “Error Handling & Debugging”

#### ORDER OF EXECUTION 
To find the source of an error, it helps to know how scripts are processed. 
The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run
![img](../images/read10.1.png)
![img](../images/read10.2.png)

### Error Handling and Debugging

* it is used to know the mistakes you did in the javascript
* ORDER OF EXECUTION : it helps in finding the source of the error
* ERROR OBJECTS : to find where is the error and there is a tools in the browser to help you in this

### HOW TO DEAL WITH ERRORS ?

* you have to debuge the script to fix the errors
* you have to handle errors gracefully
### HOW TO LOOK AT ERRORS IN CHROME?

you can look to errors by using the console, and you can type a code inside the console and it will show you the results

### HOW TO LOOK AT ERRORS IN FIREFOX?

* you can look to errors by using the console

## Some type  of error  in javascript  
>1- RangeError. 
>2-  ReferenceError.
>3-  SyntaxError. 
>4- TypeError. 
>5- URIError. 
>6- EvalError. 
>7- InternalError

### Summary
* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code. 
* Debugging is the process of finding errors. It involves a process of deduction. 
* The console helps narrow down the area in which the error is located, so you can try to find the exact error. 
* JavaScript has 7 different types of errors. Each creates itsown error object, which can tell you its line number and gives a description of the error. 
* If you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.