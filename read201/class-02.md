# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Html & CSS

### Chapter 2: “Text”

#### Headings
Browsers display the contents of  headings at different sizes. The  contents of an <h1> element is  the largest, and the contents of  an <h6> element is the smallest. The exact size at which each browser shows the headings  can vary slightly. Users can also  adjust the size of text in their browser. You will see how to control the size of text, its color,  and the fonts used when we come to look at CSS.
`<h1>` , `<h2>` , `<h3>` , `<h4>` , `<h5>` , `<h6>`.

<h1>This is Heading 1</h1>
<h2>This is Heading 2</h2>
<h3>This is Heading 3</h3>
<h4>This is Heading 4</h4>
<h5>This is Heading 5</h5>
<h6>This is Heading 6</h6>


#### Paragraghs
A paragragh is consist of one or more sentences that form a self-contained unit of discourse. The 
 start of a paragraph is indicated by a new 
 line. 
 Text is easier to understand when it is split up into units of text. For example, a book may have  chapters. Chapters can have subheadings. Under each heading there will be one or more paragraphs.

We used `<p></p>` tag to decleare the paragragh

#### Bold & Italic
By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.
The `<b>` element also represents a section of text that would be presented in a visually different way (for example key words in a 
paragraph) although the use of  the `<b>` element does not imply any additional meaning.

By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.
The `<i>` element also represents a section of text that would be said in a different way from surrounding content — such as technical terms, names of ships, foreign words, thoughts, or other terms that would usually be italicized.

#### Superscript & Subscript
`<sup>`
The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

`<sub>`
The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20 .

#### Line Breaks & Horizontal Rules
`<br />`
As you have already seen, the browser will automatically show each new paragraph or heading  on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag `<br />`.
`<hr />`
To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a horizontal rule between sections using the `<hr />` tag.


* HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).
* They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation)


### Chapter 10: “Introducing CSS”

The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.
![img](css1.png:Zone.Identifire);
![img](css2.png:Zone.Identifire);

#### Thers is a 3 ways to add CSS
+ **1-Inline CSS**
Write the CSS code in the line of HTML.
+ **2-Internal CSS**
Write the code of CSS within `<style> </style` tag in the `<head>` tag.
+ **3-External Css**
By adding this line `<link href="css/styles.css" type="text/css" rel="stylesheet" />`

#### CSS Selectors
![img](css3.png:Zone.Identifire);

+ CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.
+  Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).
+ Different types of selectors allow you to target your rules at different elements.
+ Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.
+ CSS rules usually appear in a separate document, although they may appear within an HTML page.


## JavaScripts

### Chapter 2: “Basic JavaScript Instructions”

#### STATEMENTS
A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon.

#### COMMENTS 
You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code. 

#### WHAT IS A VARIABLE?
A script will have to temporarily store the bits of information it 
needs to do its job. It can store this data in variables. 
A variable is a good name for this concept because the data stored 
in a variable can change (or vary) each time a script runs.

`var user ;`
`user=5;`

#### Data Types 
 - ***NUMERIC DATA TYPE*** : The numeric data type handles numbers.
 ` 150 ` ,`0.75` `-33.45` ect.....

 - ***STRING DATA TYPE*** : The strings data type consists of letters and other characters. 
  ` ' string ' ` , ` ' Text '`etc.....

  - *** BOOLEAN DATA TYPE*** : Boolean data types can have one of two values: true or false. 
  ` true ` , ` false ` .


+ A script is made up of a series of statements. Each statement is like a step in a recipe. 
+ Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value. 
+ Variables are used to temporarily store pieces of information used in the script. 
+ Arrays are special types of variables that store more than one piece of related information. 
+ JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false). 
+ Expressions evaluate into a single value. 
+ Expressions rely on operators to calculate a value.

### Chapter 4: “Decisions and Loops”

- #### Comparison and logical operators

##### 1-  Comparsion Operators : 
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


##### 2- Logical Operators

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





- #### LOOPS

Loops check a condition, if its retrn true, a code block it will run.
Then the condition will be checked again and if it still returns true,the code block will run again .It repeats until the condition returns false.

##### - There are Three Common types of Loops

- ** 1- FOR LOOP ** : If you need to run a code a specific number of times, use a for loop (its the most common loop ).
In a for loop, a condition is usually a counter which is used to tell how many times the loop should run.

![image](https://simplesnippets.tech/wp-content/uploads/2018/10/javascript-for-loop-flow-chart-diagram.jpg)

![image](https://cdn.educba.com/academy/wp-content/uploads/2019/10/For-Loop-in-JavaScript.png)



- ** 2- WHILE LOOP **: If you do not know how many time the code should run, you can use a **while **loop.
Here the condition can be something other than a counter, and the code will continue to loop as long as the condition is true.

![image](https://www.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-while-loop.png)

#### Switch Statment

![img](css4.png:Zone.Identifire);