# Read: 11 - Audio, Video, Images

## Chapter 16: “Images” 

### Controlling sizes of images in CSS

You can control the size of an image using the width and height properties in CSS, just like you can for any other box. Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.

### AligNing images Using CSS

In the last chapter, you saw how the float property can be used to move an element to the left or the right of its containing block, allowing text to flow around it.Rather than using the `<img>` element's align attribute, web page authors are increasingly using the float property to align images. There are two ways that this is commonly achieved:
1: The float property is added to the class that was created to represent the size of the image (such as the small class in our 
example).
2: New classes are created with names such as align-left or align-right to align the images to the left or right of the page. 
These class names are used in addition to classes that indicate the size of the image.

### Centering images Using CSS

By default, images are inline elements. This means that they flow within the surrounding text. In order to center an image, it 
should be turned into a blocklevel element using the display
property with a value of block. Once it has been made into a 
block-level element, there are two common ways in which you 
can horizontally center an image:
1: On the containing element, you can use the text-align
property with a value of center.
2: On the image itself, you can use the use the margin property 
and set the values of the left and right margins to auto.

### Background Images
`Background Images`

The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box.


### Repeating Images
`background-repeat`
`background-attachment`

> `repeat`

The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).
>`repeat-x`

The image is repeated horizontally only (as shown in the first example on the left).
>`repeat-y`

The image is repeated vertically only.
>`no-repeat`

The image is only shown once.The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values
>`fixed`

The background image stays in the same position on the page.
>`scroll`

The background image moves up and down as the user scrolls up and down the page.


### Summary 
- You can specify the dimensions of images using CSS. This is very helpful when you use the same sized images on several pages of your site.
- Images can be aligned both horizontally and vertically using CSS.
- You can use a background image behind the box created by any element on a page. 
- Background images can appear just once or be repeated across the background of the box.
- You can create image rollover effects by moving the background position of an image.
- To reduce the number of images your browser has to load, you can create image sprites.


## Chapter 19: “Practical Information”

### Summary
- Search engine optimization helps visitors find your sites when using search engines.
- Analytics tools such as Google Analytics allow you to see how many people visit your site, how they find it, and what they do when they get there.
- To put your site on the web, you will need to obtain a domain name and web hosting.
- FTP programs allow you to transfer files from your local computer to your web server.
- Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website tools (to save you writing them from scratch).