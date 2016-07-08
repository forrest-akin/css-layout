# Alphabet 

You are a front-end developer tasked with implementing the HTML/CSS for a mockup made by a designer at your company. After completing the bare minimum requirements, you will have built and styled a popular website, and understand fundamental CSS concepts, how to organize CSS code, and style a basic page. 

![Alphabet Mockup](https://github.com/melindabernrdo/css-layout/blob/master/mockup.png)

## High Level Goals of this Sprint
- Know best practices about organizing CSS code 
- Evaluate different ways of selecting elements and overriding styles 
- Understand the Box Model
- Work with floats and positioning elements
- Gain exposure working with CSS frameworks like Bootstrap 
- Gain experience to responsive design 

## Project Setup 

### Normalizing CSS
All browsers come with different default styling for elements. To even out browser consistencies and ensure styling looks the same accross all browsers, a normalizing stylesheet is used. It will handle browser quirks and bugs, preserve browser defaults, and standardize styling. Before you add custom styling to an app, it is best practice to normalize the default styles. 

A CDN stands for content delivery network. It minimizes the time it takes for visitors to access resources on a website's server by storing cached versions of the content in multiple geographic locations (PoPs). It's a best practice to link to a CDN when your application uses commonly used libraries and frameworks so users do not have to download a unique copy, and can used a cached version instead. 

- [ ] Find a [CDN](https://cdnjs.com/) to add the [Normalize.CSS](https://necolas.github.io/normalize.css/) library to your page.

### Linking to Stylesheet 
- [ ] Link your CSS file to your index.html 

### Color Picker 
A color picker allows you to find an exact hexadecimal color match for a color on a website. 
- [ ] Install the Chrome (ColorZilla Color Picker)[http://www.colorzilla.com/]

## Dev Tools 
Making a change to your app's styling and having to refresh the page to see the change is a pain. Chrome Dev Tools allows you to make changes on the fly. Note: it will not save the changes made in Dev Tools without other tools, but it is great when trying to determine what styling properties to apply. 
- Read how to use [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/?hl=en) for CSS

## Basic requirements:
Build a page that looks like http://google.com using HTML and vanilla CSS - no outside libraries! Do not look at the source code for the page until you have finished your implementation. 

### CSS Sections

Pages are composed of different sections. Each group of elements should be contained inside of another element, typically a <div></div> called a wrapper or a container. These containers compose the sections of a page.  

- [ ] Break the design into sections. Each section should have a container that will hold a sub-group of elements inside it. 
- [ ] Create container elements for the nav, main-content, and footer.
- [ ] Add a different background color to each container. This helps with positioning elements and seeing their default size.

### Default Styling 
Before jumping into styling individual sections of the page, you should figure out common styling between elements. What styling should be shared and repeated across elements? Shared styles should be implemented as classes so that it can be applied to more than one element. 
- [ ]  Set a default font size and arial on the body. The font-family is arial.
- [ ]  Set the default font color using the color picker. 
- [ ]  Change anchor tags (links) to not have an underline by default.

### Learn about the [CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)
- [ ]  Change the default display of main-content to allow margin and padding to be applied. 
- [ ]  Add padding and margin to space the elements in main-content.

### Floats and Positioning
Read about [floats and positioning](http://learn.shayhowe.com/html-css/positioning-content/)
- [ ] Position the containers for the nav, center-content, and footer appropriately. 
- [ ] Horizontally center the "Google" logo, a text input, and the buttons inside the main-content container. How does the display of the image and buttons affect how to center them?
- [ ] Position the footer so it sticks to the bottom of the page.
- [ ] Separate the footer links into two unordered lists. 
- [ ] Float the footer links to the left and the right. 

### Shared Classes 
- [ ] The two buttons below the input box share a lot of similar characteristics. Create a class .btn-main and store all shared styles in the class. 
- [ ] Apply the class to both button elements. 

### Pseudo-elements 
- [ ] Absolutely position the microphone inside the input box. 
- [ ] On hover, have the mouse turn into a pointer cursor. 
- [ ] On hover, change the border color of the input box. Use color picker to determine the right color. 

### Optimizations 
It's best practice to pre-size images to the size needed, rather than 
- [ ]  Remove the CSS properties that set a width and height to the user photo. 
- [ ]  Replace the user photo with someone amusing.
- [ ]  Size the user photo to be close to the size needed on the page. 

### Extra credit:
- [ ] Refactor the CSS to make the site responsive using vanilla css 
- [ ] Sprites are often used for images to reduce the number of image files that need to be sent over HTTP. [Create a sprite](http://www.spritebox.net/) of all the images on the page and refactor the site to use sprites. 

