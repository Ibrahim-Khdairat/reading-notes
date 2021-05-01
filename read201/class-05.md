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
