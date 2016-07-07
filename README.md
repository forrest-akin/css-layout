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

### CSS 
- [ ] Link your CSS file to your index.html 

## Dev Tools 
Making a change to your app's styling and having to refresh the page to see the change is a pain. Chrome Dev Tools allows you to make changes on the fly. Note: it will not save the changes made in Dev Tools without other tools, but it is great when trying to determine what styling properties to apply. 
- Read how to use Chrome Dev Tools for CSS [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools/iterate/inspect-styles/?hl=en)

## Basic requirements:
Build a page that looks like http://google.com using HTML and vanilla CSS - no outside libraries! Do not look at the source code for the page until you have finished your implementation. 

// TODO: give students the HTML, but no containers 
- [ ] Break the design into sections. Each section should have a container that will hold elements inside it. What containers will you have? What semantic HTML elements should you use to represent the containters and elements inside? 
- [ ] Create container elements for the nav, main-content, and footer.
- [ ] Add a class to the main-content div. 
Why not an ID? Because IDs have a higher specificity than classes, it is difficult to override their specificity if needed. Many frontend devs only use classes. 


- [ ] Position the containers for the nav, center-content, and footer appropriately. 
- [ ] Horizontally center the "Google" logo, a text input, and a search button inside the center-content container.

Extra credit:

- [ ] Make the site responsive without using a library like Bootstrap 
- [ ] Import a custom Google Font 

