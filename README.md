# Space-tourism-website
- using css grid ｜ mobile-first workflow

# Frontend Mentor - Space tourism website solution

This is a solution to the [Space tourism website challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for each of the website's pages depending on their device's screen size
- See hover states for all interactive elements on the page
- View each page and be able to toggle between the tabs to see new information

### Screenshot

![alt text](https://i.imgur.com/nus9zbu.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/chia-liu/space-tourism-site/tree/f1f26cc7613f78174610d01563e79ac5fb761d73/starter-code)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
- Converts website design elements and mockups into CSS, JavaScript (JS), and HTML code
- Create the website guideline 
- Use the templet in the guide to build a website

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

``` css 
/* -- grid template -- */
.number-title{
  grid-area: title;
}
.grid-container--destination > picture {
  grid-area: image;
}
.grid-container--destination > .tab-list {
  grid-area: tabs;
}
.grid-container--destination > .destination-info {
  grid-area: content;
}
.grid-container--destination{
    grid-template-areas: 
        '. title title .'
        '. image tabs .'
        '. image content .';      
}
/* -- blur effect -- */
.primary-navigation {
  backdrop-filter: blur( 2rem);
}
```

## Author

- Frontend Mentor - [@chia-liu](https://www.frontendmentor.io/profile/chia-liu)
- Github - [@chia-liu](https://github.com/chia-liu)


## Acknowledgments
- Thanks for Frontend Mentor challenge built by  Scrimba, and Kevin Powell
