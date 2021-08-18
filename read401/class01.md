# Read 01 : Node Ecosystem, TDD, CI/CD

### 1- Describe (in plain English) what Array.map() does

* Function iterates over an array and runs a call back for each element. The callback receives the value and the index of the array element as a parameter.


### 2- Describe (in plain English) what Array.reduce() does 
* Iterates over an array and returns the last version of the “accumulator” … in each iteration, based on the value and/or idx of the current element in the array, you have the opportunity to modify and return the accumulator. After the last iteration of the array, that accumulator value is returned to the caller.

### 3- Provide code snippets showing how to use superagent()
* With normal Promise .then() syntax
>  `let getCharacters = ()=> {`
   `superagent.get('https://swapi.dev/api/people')`
   `.then(data =>{`
    `let results = data.body.results.map(data=>{`
       `return {[data.name] : data.url}`
     `})`
     `console.log(results)`
   `}).catch(err => console.error(err))`
 `}`
 `getCharacters();`

* With async / await syntax

> `async function getResponse(){`
    `try{`
    `const response = await superagent.get(URL);`
   `console.log(response);`
    `// res.body , res.headers , res.status`
   ` }catch (err){`
       ` console.log(err);`
    `}`
`}`

 ### 4-  Explain promises as though you were mentoring a Code 301 level student 
A Promise is an object that represents the eventual completion (or failure) of an asynchronous operation, and its resulting value.The Promise object works as proxy for a value not necessarily known when the promise is created. It allows you to associate handlers with an asynchronous action’s eventual success value or failure reason.This lets asynchronous methods return values like synchronous methods: instead of immediately returning the final value, the asynchronous method returns a promise to supply the value at some point in the future.

### 5- Are all callback functions considered to be Asynchronous? Why or Why Not?
* No, not always callback functions considered to be Asynchronous, Every asynchronous function takes a function argument, but not every function that does so is asynchronous.

* For a function to be asynchronous it needs to perform an asynchronous operation. It needs to incorporate the argument callback in handling the results of this asynchronous operation. Only this way the function becomes asynchronous.