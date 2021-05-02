# Read: 05 - Operators and Loops

- ## Comparison and logical operators

### 1-  Comparsion Operators : 
You can evaluate a situation by comparing on value in the script to what you expect it might be. The result will be a boolean **True** or **False** .

- **`==`  IS EQUAL TO ** 
We use this operators to compare two values (numbers, strings and booleans) to see if they are the same .

- **`!=` IS NOT EQUAL TO**
We use this operators to compare two values (numbers, strings and booleans) to see if they are ***Not*** the same .

- **`===` STRICT EQUAL TO **
We use this operators to compare two values to see if they are the same in ***Vlaue*** and ***Data type***


- **`!==` NOT STRICT EQUAL TO **
We use this operators to compare two values to see if they are  **NOT ** the same in ***Vlaue*** and ***Data type***

- **`>` GREATER THAN **
We use this operators to check if the number in the left side is **great than** the number in the right side.

- **`<` LESS THAN **
We use this operators to check if the number in the left side is **less than** the number in the right side.


- **`>=` GREATER THAN OR EQUAL TO **
We use this operators to check if the number in the left side is **great than** or **equal** the number in the right side.


- **`<=` LESS THAN OR EQUAL TO**
We use this operators to check if the number in the left side is **less than** or **equal** the number in the right side.


### 2- Logical Operators

***Comparsion operators*** usually return single values of **True** or **False** .
***Logical operators*** allow you to compare the result of more thane one compartion operator.


- **`&&` LOGICAL AND**
This operatos is test more than one contion.

| Lgical AND Truth Table |
|------------------------|
| Left Side|| Right Side||Result of &&|
| T || T || T |
| T || F || F |
| F || T || F |
| F || F || F |


- **`||` LOGICAL OR **
This operatos is test at least one contion.


| Lgical OR Truth Table |
|------------------------|
| Left Side | | Right Side||Result of &&|
| T | | T | | T |
| T | | F | | T |
| F | | T | | T |
| F | | F | | F |


- **`!`  LOGICAL NOT **
This operator take a single boolean value and inverts it .

| Lgical OR Truth Table |
|------------------------|
| Value | | Result |
| T | | F |
| F | | T |





- ## LOOPS

Loops check a condition, if its retrn true, a code block it will run.
Then the condition will be checked again and if it still returns true,the code block will run again .It repeats until the condition returns false.

### - There are Three Common types of Loops

- ** 1- FOR LOOP ** : If you need to run a code a specific number of times, use a for loop (its the most common loop ).
In a for loop, a condition is usually a counter which is used to tell how many times the loop should run.

![image](https://simplesnippets.tech/wp-content/uploads/2018/10/javascript-for-loop-flow-chart-diagram.jpg)

![image](https://cdn.educba.com/academy/wp-content/uploads/2019/10/For-Loop-in-JavaScript.png)



- ** 2- WHILE LOOP **: If you do not know how many time the code should run, you can use a **while **loop.
Here the condition can be something other than a counter, and the code will continue to loop as long as the condition is true.

![image](https://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-while-loop.png)
