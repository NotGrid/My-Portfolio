# My Portfolio

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Acceptance Criteria](#acceptance-criteria)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview
My portfolio page for practice and potential employment.
### The challenge

Created a beginner portfolio to exercise my skill and knowledge of HTML and CSS. 

### Acceptance Criteria

GIVEN I need to sample a potential employee's previous work
- WHEN I load their portfolio
- THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
- WHEN I click one of the links in the navigation
- THEN the UI scrolls to the corresponding section
- WHEN I click on the link to the section about their work
- THEN the UI scrolls to a section with titled images of the developer's applications
- WHEN I am presented with the developer's first application
- THEN that application's image should be larger in size than the others
- WHEN I click on the images of the applications
- THEN I am taken to that deployed application
- WHEN I resize the page or view the site on various screens and devices
-THEN I am presented with a responsive layout that adapts to my viewport

### Links

- Solution URL: [https://github.com/NotGrid/My-Portfolio](https://your-solution-url.com)
- Live Site URL: [https://notgrid.github.io/My-Portfolio/](https://your-live-site-url.com)

## My process

I found it easier to create small sections on HTML and move to CSS to style the page. Once it looked styled, I then moved onto the next section of the code.

### Built with

- Semantic HTML5 markup
- CSS

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:
I learned how to use display: grid; to organize my header tags evenly.
```CSS
.nav-box ul {
  display: grid;
  gap: 20px;
  padding: 2rem 0;
  list-style: none;
  grid-template-columns: repeat(3, 1fr);
}
```
This code gave a smooth transition when hovering over the pictures.

```CSS
.bannertop:hover {
  opacity: 0.5;
  transition: .5s ease;
  box-shadow: 0 0 10px 10px#0bce4c;
}
```
This code gave a smooth transition when hovering over the pictures.


### Continued development

I plan to focus more on organizing my code to be easier to navigate and read.

### Useful resources

- [Image Overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp) - This helped me figure out how to add opacity and styling to my pictures with the hover effect.
- [CSS Grid](https://www.w3schools.com/css/css_grid.asp) - This resource was key in executing my portfolio with the ```display: grid``` layout.

## Author

- Github - [Andrew White](https://github.com/NotGrid)
- LinkedIn - [Andrew White](https://www.linkedin.com/in/andrew-white-053803235/)
