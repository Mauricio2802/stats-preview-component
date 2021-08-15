# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

Mobile:

![mobile](https://user-images.githubusercontent.com/70554280/129493892-4a407ffd-41d6-4d80-9872-fb55413f75bf.png)


Desktop:

![desktop](https://user-images.githubusercontent.com/70554280/129493899-690f7680-a1b6-453a-a8ac-b9c020e6a09f.png)


### Links

- Solution URL: [Github repository](https://github.com/Mauricio2802/stats-preview-component)
- Live Site URL: [Website](https://stats-preview-component-five.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I learn to how mix color in the same site with mix-blend-mode property:
```html
        <div class="bg-img">
          <img class="component__img img-color" alt="Card image" />
        </div>
```
```css
.component__img {
  max-width: 100%;
  content: url("../images/image-header-mobile.jpg");
  display: block;
  overflow: hidden;
}
.bg-img {
  background: var(--soft-violet);
}
.img-color {
  filter: grayscale(100);
  opacity: 0.8;
  mix-blend-mode: multiply;
}

}
```

### Continued development

This project took me work after finishing. I'll finished the project and I'll go ahead with more projects 

### Useful resources

- Comments from Frontend Mentor

## Author

- Website - I don't have a website yet
- Frontend Mentor - [@Maurice2802](https://www.frontendmentor.io/profile/Maurice2802)
- Twitter - [@maurice_cl42](https://www.twitter.com/maurice_cl42)
