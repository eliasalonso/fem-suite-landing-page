# Frontend Mentor - Suite landing page

This is a solution to the [Results suite landing page on Frontend Mentor](https://www.frontendmentor.io/challenges/suite-landing-page-tj_eaU-Ra). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Live Site URL: (https://heroic-meringue-276f7d.netlify.app/)

## My process

Setting Up the HTML Structure: I started by creating the basic HTML structure using the <!DOCTYPE html> declaration and <html>, <head>, and <body> tags. Inside the <head> tag, I added meta tags for character encoding and viewport settings. I also included external CSS files using <link> tags and added a favicon.

Styling with CSS: I defined custom CSS variables using :root to set up the color palette and some layout properties like padding and font families.

Resetting Default Styles: I reset some default styles using the universal selector * to set box-sizing to border-box and remove default margins.

Typography Tweaks: I improved the text rendering by setting line-height to 1.5 and using -webkit-font-smoothing: antialiased for better readability.

Image and Media Defaults: I adjusted the default display for images, videos, and SVG elements to make them responsive and fit within their containers.

Form Element Styles: I removed the default form element styles to have better control over the form components' appearance.

Text Overflow Handling: I ensured that text won't overflow its container by using overflow-wrap: break-word for specific elements.

Creating a Root Stacking Context: I isolated the #root and #__next elements by using isolation: isolate to create a root stacking context.

Styling the Header: I designed the header section with a logo and a "Request Beta Access" button. I used flexbox to align the elements and added styles to the button for visual feedback on hover.

The First Section: I created the first section with a curved line image and a heading with dynamic spans. I used absolute positioning to position the curved line image and added styles to the heading and paragraph.

The Second Beta Access Button: I designed the second "Request Beta Access" button in the first section, similar to the one in the header, with appropriate styles and hover effects.

The First Article Container: I structured the first article container with images of a smartphone in different orientations. I used media queries to display the appropriate image based on the device's screen size.

Info Article Container: I created an info container with three headings displaying numbers and their respective categories. I used flexbox to arrange them in a row and added appropriate styles.

Main Container: I designed the main container with an image, a small curved line image, and text. I used grid layout to position elements and added styles for alignment and positioning.

Footer Container: I structured the footer container with the logo, copyright text, and social media icons. I used flexbox to align the elements and added padding and margins.

Responsive Design: I made the website responsive by using media queries to adjust the layout and styles for different screen sizes. I handled various breakpoints to ensure a consistent user experience on different devices.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### Useful resources

- [Custom CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me to create a really good responsive website. I really liked this reset and will use it again.

## Author

- Frontend Mentor - [@eliasalonso](https://www.frontendmentor.io/profile/eliasalonso)
- Instagram - [@eliasmaestro](https://www.instagram.com/eliasmaestro)
