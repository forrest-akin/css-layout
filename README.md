# Google It 

You are a front-end developer tasked with implementing the HTML/CSS for a mockup made by a designer at your company. After completing the bare minimum requirements, you will have built and styled a popular website, and understand fundamental CSS concepts, how to organize CSS code, and style a basic page. 

![GoogleIt Mockup](https://github.com/melindabernrdo/css-layout/blob/master/mockup.png)

## High Level Goals of this Sprint
- Know best practices for working with CSS code 
- Evaluate different ways of selecting and classifying elements 
- Understand the Box Model and display properties 
- Work with positioning elements and floats 
- Gain exposure to pseudo-classes and background images

## Project Setup 

### Normalizing CSS
All browsers come with different default styling for elements. To even out browser consistencies and ensure styling looks the same accross all browsers, a normalizing stylesheet is used. Before you add custom styling to an app, it is best practice to normalize the default styles. 

A CDN stands for content delivery network. It minimizes the time it takes for visitors to access resources on a website's server by storing cached versions of the content in multiple geographic locations (PoPs). It's a best practice to link to a CDN when your application makes use of commonly used libraries and frameworks/ 

- [ ] Find a [CDN](https://cdnjs.com/) to add the [Normalize.CSS](https://necolas.github.io/normalize.css/) library to your page.

### Linking to Stylesheet 
- [ ] Link your CSS file to your index.html 

### Color Picker 
A color picker allows you to find an exact hexadecimal color match for a color on a website. 
- [ ] Install the Chrome [ColorZilla Color Picker](http://www.colorzilla.com/)

## Dev Tools 
Refreshing the page every time you make a change to your page's styling is a pain. Chrome Dev Tools allows you to make changes on the fly. Note: it will not save the changes made in Dev Tools to your css stylesheet without other tools, but it is useful when testing out styling properties to apply. 
- Read how to use [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/?hl=en) for CSS

## Basic requirements:
Build a page that looks like http://google.com using HTML and vanilla CSS - no outside libraries! Do not look at the source code for the page until you have finished your implementation. 

### CSS Sections

Pages are composed of different sections. Each group of elements should be contained inside of another element, typically a div called a wrapper or a container. These containers compose the sections of a page.  

- [ ] Break the design into sections. Each section should have a container that will hold a sub-group of elements inside it. Determine what html elements on index.html are a part of what section.  
- [ ] Create a container element for the main-content.
- [ ] Add a different background color to each container. This helps with positioning elements and knowing their default size. 

### Default Styling 
Before jumping into styling individual sections of the page, think about common styling shared between elements. Any styling that should be applied to all elements of the same type should be defined before styling for specific sections. Add default styling for the sprint to the top of the css sheet. 
- [ ] Set a default font size and arial on the body. The font-family is arial.
- [ ] Set the default font color. Use the color picker to determine the color. 
- [ ] Change anchor tags (links) to not have an underline by default and be the correct hue of gray.
- [ ] Change the ul to not show bullets for each li item.
- [ ] Change the default display of the li such that each li item will appear on the same line. 

Learn about the [CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
#### nav 
- [ ] Apply margin and/or padding between each li to vertically center the icons. 
- [ ] Vertically align the li items to the top. 
- [ ] Add a width and height property to image and make the user pic round using the border-radius property. 

#### .main-content 
- [ ] Change the display of input so it will be on its own line. Use width and height properties to size it correctly.
- [ ] Add padding and margin to space the elements in main-content.

### Floats and Positioning
Read about [floats and positioning](http://learn.shayhowe.com/html-css/positioning-content/)
- [ ] Position the containers for the nav, main-content, and footer appropriately. 
- [ ] Horizontally center the "Google" logo, a text input, and the buttons inside the main-content container. How does the display of the image and buttons affect how to center them?
- [ ] Position the footer so it sticks to the bottom of the page.
- [ ] Separate the footer links into two unordered lists. 
- [ ] Float one section of the <ul></ul> to the right. 

### Shared Classes 
- [ ] The two buttons below the input box share a lot of similar characteristics. Create a class .btn-main and store all shared styles in the class. 
- [ ] Apply the class to both button elements. 

### Pseudo-classes
Read about [Pseudo-classes](http://www.w3schools.com/Css/css_pseudo_classes.asp)
- [ ] Use a background image to center right position microphone.png on the input box
- [ ] On hover state for <a></a>, have the mouse turn into a pointer cursor. 
- [ ] On hover state or input, change the border color of the input box. Use color picker to determine the right color. 
- [ ] On focus state for input, change the border color of the input box. Use color picker to determine the right color. 

### Optimizations 
It's best practice to pre-size images to the size needed, rather than using larger than necessary images that are sized down using CSS selectors. 
- [ ]  Resize the user pic, icons, and user photo to be the appropriate size by default. 
- [ ]  Remove the CSS properties and classes that set a width and height to the user pic and icons. 
- [ ]  Size the user pic and icons to be close to the size needed on the page. 

Congrats! Your page should look extremely close to the mockup. Take a second look at the mockup and compare it with your styled page. Fix any styling that is not an exact replica of the mockup. 

### Extra credit:
- [ ] Sprites are often used for images to reduce the number of image files that need to be sent over HTTP. [Create a sprite](http://www.spritebox.net/) of all the images on the page and refactor the site to use sprites. 
- [ ] Implement [this site](https://www.palantir.com/). Use a static photo for the jumbotron. 
- [ ] Refactor to make the [site responsive](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/) using vanilla css (no Bootstrap!). 
- [ ] Refactor the site to use a responsive video header. 

