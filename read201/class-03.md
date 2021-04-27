# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow

## HTML 

### Chapter 3: “Lists”
There are lots of occasions when we need to use lists. HTML provides us with three different types :
 #### 1- Ordered List
 `<ol>`
The ordered list is created with the `<ol>` element.
`<li>`
Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag. (The li stands for list item.).
 #### 2- Unordered List
 `<ul>`
The unordered list is created with the `<ul>` element.
`<li>`
Each item in the list is placed between an opening `<li>` tag and a closing `</li>` tag. (The listands for list item.)
 #### 3- Definition lists
 `<dl>`
The definition list is created with the `<dl>` element and usually consists of a series of terms and their definitions.
Inside the `<dl>` element you will usually see pairs of `<dt>` and `<dd>` elements.
`<dt>`
This is used to contain the term being defined (the definition term). 
`<dd>`
This is used to contain the definition. Sometimes you might see a list where there are two terms used for the same definition or two different definitions for the same term.

### Chapter 13: “Boxes”

At the beginning of this section on CSS, you saw how CSS treats each HTML element as if it lives in its own box.
#### Box Dimensions
`width, height`
#### Limiting Width
`min-width, max-width`
#### Limiting Height
`min-height, max-height`
#### Overflowing Content
`overflow`
`overflow: hidden;` , , `overflow: scroll;`

#### ***Border, Margin  & Paddin***
##### 1- Border
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

**Border Width**
`border-width`
`border-top-width`
`border-right-width`
`border-bottom-width`
`border-left-width`

**Border Style**
`border-style`
`border-style: solid;`
`border-style: dotted;`
`border-style: dashed;`
`border-style: double;`
`border-style: groove;`
`border-style: ridge;`
`border-style: inset;`
`border-style: outset;`

**Border Color**
`border-color`
`border-top-color`
`border-right-color`
`border-bottom-color`
`border-left-color`




##### 2- Margin
Margins sit outside the edge of the border. You can set the 
width of a margin to create a gap between the borders of two 
adjacent boxes.

**Margin**
`margin`
`margin-top`
`margin-right`
`margin-bottom`
`margin-left`
##### 3- Padding
Padding is the space between the border of a box and any 
content contained within it. Adding padding can increase the 
readability of its contents.

**Padding**
`padding`
`padding-top`
`padding-right`
`padding-bottom`
`padding-left`

#### Change Inline/Block
**display**
`display: inline`
`display: block`
`display: inline-block`
`display: none`

#### Hiding Boxes
`visibility`
`visibility: hidden;`
`visibility: visible;`

+ CSS treats each HTML element as if it has its own box. 
+ You can use CSS to control the dimensions of a box.
+ You can also control the borders, margin and padding 
for each box with CSS.
+ It is possible to hide elements using the display and 
visibility properties.
+ Block-level boxes can be made into inline boxes, and 
inline boxes made into block-level boxes.
+ Legibility can be improved by controlling the width of 
boxes containing text and the leading.
+ CSS3 has introduced the ability to create image 
borders and rounded borders


## JavaScript

### Chapter 2: “Basic JavaScript Instructions”
#### ARRAYS
An array is a special type of variable. It doesn't just store one value; it stores a list of values.
#### CREATING AN ARRAY
You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array). 
The values are assigned to the  array inside a pair of square brackets, and each value is separated by a comma. The 
values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array. 
This technique for creating an array is known as an array 
literal. It is usually the preferred method for creating an array. You can also write each value on 
a separate line.
`colors= ['white',` 
`'black',` 
`'custom']`

#### VALU ES IN ARRAYS
Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one). 

#### ACCESSING & CHANGING  VALUES IN AN ARRAY
 `//Create the array `
`var colors = ['white', 
'black' , 
'custom']; `
 `//Update the third item in the array `
`colors[2] = 'beige ' ; `
`//Get the element with an id of colors` 
`var el = document .getElementByid(' colors') ; `
`//Replace with third item from the array `
`el .textContent = colors[2];`


### Chapter 4: “Decisions and Loops”
SWITCH STATEMENTS 
A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value. 
Here, the variable named 1 eve l is the switch value. If the value of the l eve 1 variable is the string One, then the code for the first case is executed. If it is Two, the second case is executed. If it is Three, the  third case is executed. If it is none of these, the code for the defaul t case is executed. 
The entire statement lives in one code block (set of curly braces), and a colon separates the option from the statements that are to be run if the case matches the switch value. At the end of each case is the break keyword. It tells the JavaScript interpreter that it has finished with this switch statement and to proceed to run any subsequent code that appears after it. 
IF ... ELSE 
• There is no need to provide an el se 
option. (You can just use an if 
statement.) 
• With a series of if statements, they are 
all checked even if a match has been found 
(so it performs more slowly than switch). 

`switch (level) { `
`case 'One ': `
`title= 'Level 1 ' ;` 
`break; `
`case 'Two': `
`tit 1 e = ' Level 2 ' ;` 
`break; `
`case ' Three' : `
`title = 'Level 3' ;` 
`break ; `
`default : `
`title= 'Test';` 
`break;` 
SWITCH 
• You have a default option that is run if none of the cases match. 
• If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f statements).