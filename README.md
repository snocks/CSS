# CSS
### *The CSS Box Model*
All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.
The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t34.0-12/16426776_744692855693093_1436418574_n.jpg?oh=7ebec5afa81a8bca7649eb19f0841d16&oe=5891AC86)

#### Explanation of the different parts:

1. Content - The content of the box, where text and images appear
2. Padding - Clears an area around the content. The padding is transparent
3. Border - A border that goes around the padding and content
4. Margin - Clears an area outside the border. The margin is transparent

The box model allows us to add a border around elements, and to define space between elements.

##### Example :

div {

    width: 300px;
    border: 25px solid green;
    padding: 25px;
    margin: 25px;
    }




### Responsive vs mobile-first design

Mobile first and responsive Web Design (RWD) are huge buzz words in the web design world. But, are they actually different things or is responsive Design just a way to help you create a mobile first design?

You might or might not already be familiar with the term “responsive”. It is used to describe the possibility of websites adapting to various output devices. The layout, fonts, image sizes etc. change and or scale according to the size of the browser. This principle enables good readability and usability on desktops, tablet.

Graceful degradation used to be the norm, meaning that designers created for the newest and biggest device, and the smaller, older devices got the leftovers. The new norm is progressive enhancement, which means starting the project at the bottom and working your way up. More people use mobile devices today than they ever have before, so now the mobile view of a site is never placed on the back-burner or last round of testing.

The term “mobile first”, being very descriptive, already gives us a good hint of what to expect: primarily focusing on development for mobile devices. The common responsive approach works with the desktop browser as the basis, and offers alternative, scaled down versions for other device/browser sizes. That works via CSS media queries, which check the browser size and adjust the layout and styling according to that.



![alt text](http://metamonks.com/wp-content/uploads/responsive-vs-mobile-first-webdesign-022-1024x689.png "Responsive vs mobile-first design")

### Grid system

Over the past few years CSS grid systems have grown a lot in popularity, quickly becoming considered best practice for rapid layout scaffolding. As a result, there has been no shortage of frameworks popping up offering their own grid systems trying to garner favor.

What’s Grid System?
A grid system is a structure that allows for content to be stacked both vertically and horizontally in a consistent and easily manageable fashion. Additionally, grid system code is giving it a high degree of portability so that it may be adopted on new projects.


Now, When we want to design a web page, we should consider the size of screens of devices, which divided into:
1. xs 
2. sm 
3. md 
4. lg

![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t35.0-12/16388602_1839734452907384_288964415_o.png?oh=0b255e1a7d1b3815cec1e91571cef459&oe=58914AF4 "Medium & Large")

![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t35.0-12/16409761_1839734462907383_893359892_o.png?oh=6e635475f8b19ee5a3048703e0ba4b7f&oe=58914AC0 "small devices ")

![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t35.0-12/16409369_1839734456240717_1914908926_o.png?oh=987dfd71d95cf130692a413c05844b44&oe=589141FF "Responsive vs mobile-first design")


#### Advantages:

 Organizing a content into distributed columns and rows.

The layouts that have adapted the grid style look clean and structured,  not chaotic.

 Offers a level of stability to the structure of web design that establishes visual unity between a series of related pieces. 

It is easy if we need to move the content right or left.

#### Disadvantages:

The layouts based on grids are not appropriate in all cases and sometimes cannot satisfy a specific web design style.

Grids may limit the design by forcing it to be constrained and even confined.

### What is a CSS Preprocessor?

A CSS preprocessor is a scripting language that extends CSS and is compiled into regular CSS syntax. A browser can only understand CSS, which at times may not be enough to write clean and reusable rules. Using only CSS, the designer/developer is not able to reuse a collection of rules in multiple selectors which had unclear pieces of data across a stylesheet. To overcome most of these limitations, the concept of a preprocessor was created. It offered an advanced way of writing CSS that extends the basic functionalities. This advanced code is later compiled as normal CSS code that the browser will understand.

There are three main preprocessors – *SASS*, *LESS* and *STYLES*.
Each CSS preprocessor has its own unique way of accomplishing the same task, but have some  differences in the advanced usage.

### Why would you use one?
1. It will make your CSS DRY means Don’t repeat yourself. For example:

![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t34.0-12/16441646_1802172956714169_602525465_n.jpg?oh=afc5734c05f8b4c497851c59bf4b7e1c&oe=5891736D)
it become:
![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t34.0-12/16344508_1802173736714091_1975047297_n.jpg?oh=b069cdce5e706e2ebddd93704fd77c7d&oe=5891AD7E)

2. 	It allow you to  perform any Arithmetical and Logical task
* **If/Else Statements**
Control directives and expressions help to build similar style definitions according to matched conditions or variables
![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t34.0-12/16395692_1802175436713921_102095747_n.jpg?oh=08320bb3c0a0d627a68024d5f09a8c86&oe=5891B7A1)

* **Loops**
Loops are useful when iterating through an array or creating a series of styles as in grid widths. 
![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t34.0-12/16443342_1802175813380550_252952704_n.jpg?oh=fb4bd57eaf7159b258b772784890c751&oe=5891B557)
3. It will save your time. You will be impressed at how much time you will save when you aren’t forced to write the same code over and over again. We can all use a little more free time.











