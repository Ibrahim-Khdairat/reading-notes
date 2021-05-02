# Read: 05 - HTML Images; CSS Color & Text

## Chapter 5: “Images” 

### Choosing Images for Your Site
A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

### Storing Images on Your Site
If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.

### Adding Images
`<img>`
to add an image into the page you need to use an  `<img>` element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
`src`
This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images — relative URLs.
`alt`
This provides a text description of the image which describes the image if you cannot see it.
`title`
You can also use the title attribute with the `<img>` element 
to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.

### Height & Width of Images
`height`
This specifies the height of the image in pixels.
`width`
This specifies the width of the image in pixels.

### Where to Place Images in Your Code
> 1: before a paragraph

The paragraph starts on a new line after the image.

>2: inside the start of a paragraph

The first row of text aligns with the bottom of the image.

>3: in the middle of a paragraph

The image is placed between the words of the paragraph that it appears in.


#### Summary
+ The <img> element is used to add images to a 
web page.
+ You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image.
+ You should save images at the size you will be using them on the web page and in the appropriate format.
+ Photographs are best saved as JPEGs; illustrations or logos that use flat colors are better saved as GIFs.

## Chapter 11: “Color”

### Foreground Color
`color`
>rgb values

These express colors in terms of how much red, green and 
blue are used to make it up. For example: rgb(100,100,90)
 
 >hex codes

These are six-digit codes that represent the amount of red,green and blue in a color, preceded by a pound or hash # 
sign. For example: #ee3e80

>color names

There are 147 predefined color names that are recognized 
by browsers. For example: Blue.

### Background Color
`background-color`
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box. You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values,ex codes, and color names 
(covered on the next page).

### Understanding Color
Every color on a computer screen is created by mixing amounts of red, green, and blue.
Computer monitors are made up of thousands of tiny squares 
called pixels (if you look very closely at your monitor you 
should be able to see them).

The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue.


### Summary
+ Color not only brings your site to life, but also helps convey the mood and evokes reactions.
+ There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
+ Color pickers can help you find the color you want.
+ It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
+ CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
+ CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.


## Chapter 12: “Text”

### Specifying Typefaces
`font-family`
The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.

### Size of Type
`font-size`
The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font.

### More Font Choice
`@font-face`
@font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.

### Bold
`font-weight`
The font-weight property allows you to create bold text. There are two values that this property commonly takes:
>`normal`

This causes text to appear at a normal weight.
>`bold`

This causes text to appear bold.


### Italic
`font-style`


If you want to create italic text, you can use the font-style property. There are three values this property can take:
>`normal`

This causes text to appear in a normal style (as opposed to italic or oblique).
>`italic`

This causes text to appear italic.
>`oblique`

This causes text to appear oblique.

### UpperCase & LowerCase
`text-transform`

>`uppercase`

This causes the text to appear uppercase.
>`lowercase`

This causes the text to appear lowercase.
>`capitalize`

This causes the first letter of each word to appear capitalized.

### Underline & Strike
`text-decoration`

>`none`

This removes any decoration already applied to the text.

>`underline`

This adds a line underneath the text.

>`overline`

This adds a line over the top of the text.

>`line-through`

This adds a line through words.

>`blink`

This animates the text to make it flash on and off (however this is generally frowned upon, as it is considered rather annoying).

### Leading
`line-height`

### Letter & Word Spacing
`letter-spacing` , `word-spacing`

### Alignment
`text-align`

>`left`

This indicates that the text should be left-aligned.
>`right`

This indicates that the text should be right-aligned.
>`center`

This allows you to center text.
>`justify`

This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box.


### Vertical Alignment
`vertical-align`

It is more commonly used with inline elements such as `<img>`,`<em>`, or `<strong>` elements. When used with these elements, it performs a task very similar to the HTML align attribute used on the `<img>` element.

>`baseline`
`sub`
`super`
`top`
`text-top`
`middle`
`bottom`
`text-bottom`

### Drop Shadow
`text-shadow`
Example:  `text-shadow: 1px 1px 0px #000000;`

### First Letter or Line
`:first-letter` , `:first-line`

Example : 
`p.intro:first-letter {font-size: 200%;}`
`p.intro:first-line {font-weight: bold;}`


### Styling Links
`:link` , `:visited`

>`:link`

This allows you to set styles for links that have not yet been visited. 
>`:visited`

This allows you to set styles for links that have been clicked on. 

### Responding to Users
`:hover` , `:active` , `:focus`

>`:hover`

This is applied when a user hovers over an element with a pointing device such as a mouse. This has commonly been used to change the appearance of links and buttons when a user places their cursor over them. It is worth noting that such events do not work on devices that use touch screens (such as the iPad)because the screen is not able to tell when someone is hovering their finger over an element.

>`:active`

This is applied when an element is being activated by a user; for example, when a button is being pressed or a link being clicked. Sometimes this is used to make a button or link feel more like it is being pressed by changing the style or position of the element slightly.

>`:focus`

This is applied when an element has focus. Any element that you can interact with, such as a link you can click on or any form control can have focus.


### Summary
+ There are properties to control the choice of font, size, weight, style, and spacing.
+ There is a limited choice of fonts that you can assume most people will have installed.
+ If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
+ You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.
+ You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.
