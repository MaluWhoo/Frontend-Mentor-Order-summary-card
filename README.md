# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](images/screenshot.jpg.jpeg)

![](images/screenshot-2.jpg.jpeg)

### Links

- Live Site URL: [GitHub Pages](https://maluwhoo.github.io/Frontend-Mentor-Order-summary-card/)

## My process

### Built with

- Semantic HTML5 markup  
- CSS custom properties  
- Flexbox  
- Mobile-first workflow

### What I learned

During this project, I practiced and improved several skills:

- Building **responsive layouts** using a mobile-first approach.  
- Positioning and aligning elements with **Flexbox**.  
- Applying **hover states** to buttons and links for better user interaction.  

#### Example of a hover effect I implemented:

```css
.button {
    padding: 1rem;
    margin: 0 auto;
    width: 80%;
    border: none;
    border-radius: 10px;
    box-shadow: 0px 20px 20px rgba(56, 42, 225, 0.19);
    background-color: #382AE1;
    color: white;
    font-size: 95%;
    font-weight: 700;
    cursor: pointer;
    height: 50px;
    transition: background-color 0.3s;
    display: block;
}

.button:hover {
    background-color: #766CF1;
}
```

### Continued development

- Improve responsiveness across different screen sizes.  
- Practice using CSS variables more effectively.  
- Deepen my understanding of accessibility (proper use of `aria-*` attributes and color contrast).  
- Study best practices for organizing CSS (such as BEM and CSS architecture).

## Author

- GitHub - [MaluWhoo](https://github.com/MaluWhoo)
- Frontend Mentor - [@MaluWhoo](https://www.frontendmentor.io/profile/MaluWhoo)
