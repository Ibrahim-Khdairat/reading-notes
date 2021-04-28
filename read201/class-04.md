# Read: 04 - HTML Links, CSS Layout, JS Functions

## HTML 
### Chapter 4: “Links” 

#### Writing Links
Links are created using the `<a>` element. Users can click on anything between the opening `<a>`tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.
`<a href="http://www.imdb.com">IMDB</a>`

For example if we want to link other pages on the same website : 
`<p>`
`<ul>`
 `<li><a href="index.html">Home</a></li>`
 `<li><a href="about-us.html">About</a></li>`
 `<li><a href="movies.html">Movies</a></li>`
 `<li><a href="contact.html">Contact</a></li>`
`</ul>`
`</p>`
#### Directory Structure
On larger websites it's a good idea to organize your code by placing the  pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.

#### Relative URLs
Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.
#### Email Links
`mailto:`
Example : `<a href="mailto:ibrahimkuderat@gmail.com">Email Ibrahim</a>`
#### Opening Links in a New Window
`target`
Example : `<a href="http://www.google.com" target="_blank">Google</a>`

Links are created using the `<a>` element.
+ The `<a>` element uses the href attribute to indicate the page you are linking to.
+ If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
+ You can create links to open email programs with an email address in the "to" field.
+ You can use the id attribute to target elements within a page that can be linked to.
### Chapter 15: “Layout” 
#### Key Concepts in Positioning Elements
##### 1-Building Blocks
CSS treats each HTML element as if it is in its 
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use 
borders, margins, padding, and background colors.
##### 2-Containing Elements
If one block-level element sits inside another 
block-level element then the outer box is 
known as the containing or parent element.
It is common to group a number of elements together inside a `<div>`(or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The `<div>` element that contains this group of elements is then referred to as the containing element.
##### 3- Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

>Normal flow

Every block-level element appears on a new line, causing 
each item to appear lower down the page than the previous one. Even if you specify the width of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else).
***The paragraphs appear one after the other, vertically down the page***

>Relative Positioning

This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.
***The second paragraph has been pushed down and right from where it would otherwise have been in normal flow***


>Absolute positioning

This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.
***The heading is positioned to the top right, and the paragraphs start at the top of the screen (as if the heading were not there).***

* To indicate where a box should be positioned, you may also need to use box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. (You will meet these when we introduce the positioning schemes on the following pages.)

>Fixed Positioning

This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning  do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.
***The heading has been placed in the center of the page and 25% from the top of the screen. (The rest appears in normal flow.)***

>Floating Elements

Floating an element allows you to take that element out of normal flow and position it to the far left or right of a 
containing box. The floated element becomes a block-level element around which other content can flow.
***The heading has been floated to the left, allowing the paragraphs of text to flow around it.***

## JavaScript
### Chapter 3: “Functions, Methods, and Objects”
#### WHAT IS A FUNCTION?
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 

![img](javasc1.PNG);
![img](javasc2.PNG);
![img](javasc3.PNG);
![img](javasc4.PNG);

* #### 6 Reasons for Pair Programming
##### 1- Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making. Research indicates that pair programing takes slightly longer, but produces higher-quality code that doesn’t require later effort in troubleshooting and debugging (let alone exposing users to a broken product). So, in the long-run, it’s often actually more efficient than two people working on separate features. When coming up with ideas and discussing solutions out loud, two programmers may come to a solution faster than one programmer on their own. Also, when the pair is stuck, both programmers can research the problem and reach a solution faster. Researches also identified pairing enhances technical skills, team communication, and even enjoyability of coding in the workplace.

##### 2-Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. It is harder to procrastinate or get off track when someone else is relying on you to complete the work. Popping open your Facebook timeline is just that less enticing when someone else is looking at your screen.
##### 3- Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of. If one developer has a unique approach to a specific problem, pair programming exposes the other developer to a new solution.
##### 4- Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities. Pair programming not only improves programming skills, but can also help programmers develop their interpersonal skills. When just grabbing the keyboard and taking over isn’t an option, getting good at finding the right words is a skill unto itself.
##### 5- Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing so, companies can get a better feel for how an applicant will fit into the team and their collaboration style.
##### 6- Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.