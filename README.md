# CSS
### The CSS Box Model
All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.
The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:
![alt text](https://scontent-fra3-1.xx.fbcdn.net/v/t34.0-12/16426776_744692855693093_1436418574_n.jpg?oh=7ebec5afa81a8bca7649eb19f0841d16&oe=5891AC86)

Explanation of the different parts:
•	Content - The content of the box, where text and images appear
•	Padding - Clears an area around the content. The padding is transparent
•	Border - A border that goes around the padding and content
•	Margin - Clears an area outside the border. The margin is transparent


### Responsive vs mobile-first design

Mobile first and responsive Web Design (RWD) are huge buzz words in the web design world. But, are they actually different things or is responsive Design just a way to help you create a mobile first design?

You might or might not already be familiar with the term “responsive”. It is used to describe the possibility of websites adapting to various output devices. The layout, fonts, image sizes etc. change and or scale according to the size of the browser. This principle enables good readability and usability on desktops, tablet.

Graceful degradation used to be the norm, meaning that designers created for the newest and biggest device, and the smaller, older devices got the leftovers. The new norm is progressive enhancement, which means starting the project at the bottom and working your way up. More people use mobile devices today than they ever have before, so now the mobile view of a site is never placed on the back-burner or last round of testing.

The term “mobile first”, being very descriptive, already gives us a good hint of what to expect: primarily focusing on development for mobile devices. The common responsive approach works with the desktop browser as the basis, and offers alternative, scaled down versions for other device/browser sizes. That works via CSS media queries, which check the browser size and adjust the layout and styling according to that.

![alt text](http://metamonks.com/wp-content/uploads/responsive-vs-mobile-first-webdesign-022-1024x689.png "Responsive vs mobile-first design")

