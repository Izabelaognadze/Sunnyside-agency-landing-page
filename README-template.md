# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot
<!-- aq davamato-->
![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
<!-- aq davamato-->

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Responsive Design 
- Javascript
- Sass - stylesheet language


### What I learned
```css
.grid{
        grid-template-columns: repeat(1, 1fr);
    }
    .info-btn:nth-of-type(1){
        order: 2;
    }
    .info-btn:nth-of-type(2){
        order: 1;
    }
```

```html
<div class="hamburger">
  <span class="bar"></span>
  <span class="bar"></span>
  <span class="bar"></span>
</div>
```

```css
.bar {
  -webkit-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
}
```

```js
document.querySelector("nav-link").forEach(n => n.addEventListener("click",() =>{
    hamburger.classList.remove("active");
    navMenu.classList.remove("active");
}))
```


### Useful resources

- [Example resource 1](https://codepen.io/tutsplus/pen/edOLMb) - This helped me for grid section.
- [Example resource 2](https://www.youtube.com/watch?v=flItyHiDm7E&list=LL&index=2&t=608s) - This helped me for header section.

## Author

- Linkedin - [@izabela-ognadze](https://www.linkedin.com/in/izabela-ognadze/)
- Frontend Mentor - [@Izabelaognadze](https://www.frontendmentor.io/profile/Izabelaognadze)
- Twitter - [@izabelaog](https://twitter.com/izabelaog)



