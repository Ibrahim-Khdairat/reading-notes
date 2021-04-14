# Read: 04a - Dynamic web pages with JavaScript

- ## Chapter-1 : HOW HTML, CSS,& JAVASCRIPT FIT TOGETHER

### 1- <HTML> 

CONTENT LAYER
. html files
This is where the content of the page lives. The HTML gives the page structure and adds semantics. Where possible, aim to keep the three languages in separate files, with the HTML page linking to CSS and JavaScript files.


### 2-{CSS}

PRESENTATION LAYER
. css files
The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).
Programmers often refer to this as a separation of concerns. 8 THE ABC OF PROGRAMMING Each language forms a separate layer with a different purpose. Each layer, from left to right. builds on the previous one .


### 3- Javascript()

BEHAVIOR LAYER
.js files
This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as possible in separate files .

*** How do i write a script for a webpages ? ***

- It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.

- The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the <link> element can be used to load a CSS file).

- If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.



- ## Chapter-2 : Basic Javascript Instruction

### 1- STATEMENTS
A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon. 


#### 1- If Statment : 
if (condition)
{
  Here we write the state 
}

#### 2- Variable :
- var Name = 'Value'  ***as a string.***
- var Num = 5 ;        ***as a number***
- var State = true; or false; ***save as true or false***


### 2- COMMENTS

You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 

 ``/ * Th i s script displays a greeting to the user based upon the current time. It is an example from JavaScript & jQuer y book * /``

 ### 3- Variables

 A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.
 A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs. 


 `` var Quantity = ' ' ; `` *** This is the way to add a variable .***

 **- Data Types** :
 - ***NUMERIC DATA TYPE*** : The numeric data type handles numbers.
 ` 150 ` ,`0.75` `-33.45` ect.....

 - ***STRING DATA TYPE*** : The strings data type consists of letters and other characters. 
  ` ' string ' ` , ` ' Text '`etc.....

  - *** BOOLEAN DATA TYPE*** : Boolean data types can have one of two values: true or false. 
  ` true ` , ` false ` .