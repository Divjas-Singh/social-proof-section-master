# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [https://divjas-singh.github.io/social-proof-section-master/](https://divjas-singh.github.io/social-proof-section-master/)
- Live Site URL: [https://github.com/Divjas-Singh/social-proof-section-master](https://github.com/Divjas-Singh/social-proof-section-master)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles



### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.
```css
@media screen and (max-width:1350px) {
    html{
        font-size: 50%;
    }
}
@media screen and (max-width:1133px) {
    .rating{
        grid-auto-flow:row;
        grid-template-rows: max-content auto;
    }
}
@media screen and (max-width:800px) {
    section{
        grid-template-rows: auto auto;
        gap: 0rem 3rem;
       
    }
    #comment1,    #comment2 , #comment3 {
        align-self: auto;
    }
    #rating1, #rating, #rating3{
        justify-self: auto;
    }
    .rating{width: auto;}
}
@media screen and (max-width:600px) {
    main{
        width: 90%;
    }
    body{
        background-image: url('./images/bg-pattern-bottom-mobile.svg'),url('./images/bg-pattern-top-mobile.svg');
    }

}
```

### Useful resources

- [W3schools](https://www.w3schools.com/default.asp) 


## Author

- Website - [Divjas Singh Anand]
- Frontend Mentor - [@Divjas-Singh](https://www.frontendmentor.io/profile/Divjas-Singh)




