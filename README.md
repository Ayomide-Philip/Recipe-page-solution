# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


  ### Screenshot

![](./preview.jpg)


## Overview
This is a webpage i designed for my challenge. In this chsllenge i used some important CSS property to make it 
look responsive, note this site wont display on any screen less than 320px
**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
### What I learned

```html
<div class="grid-container">
  <div>Calories</div>
  <div class="measurment">277kcal</div>
  <div>Crabs</div>
  <div class="measurment">0g</div>
  <div>Protein</div>
  <div class="measurment">20g</div>
  <div>Fat</div>
  <div class="measurment">22g</div>
</div>
```
```css
.grid-container{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr;
    justify-items: flex-start;
    row-gap: 10px;
    font-family: cursive;
}
```
If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


## Author

- Frontend Mentor - [@Ayomide-Philip](https://www.frontendmentor.io/profile/@Ayomide-Philip)
- Facebook - [Da Emperor](https://facebook.com/ayo.areo.90)
