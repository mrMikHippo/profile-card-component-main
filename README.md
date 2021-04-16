# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

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

- Build out the project to the designs provided

### Screenshot

![Design preview for the Profile card component coding challenge](./design/Screenshot.png)

### Links

- Solution URL: [github.com/mrMikHippo/profile-card-component-main](https://github.com/mrMikHippo/profile-card-component-main)
- Live Site URL: [https://mrmikhippo.github.io/profile-card-component-main/](https://mrmikhippo.github.io/profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Methodology

### What I learned

In this challenge, I used a new approach in HTML class naming BEM methodology.

```html
<div class="card">
  <div class="card__top-back"></div>
  <div class="card__description">
      <img class="card__image" src="" alt="">        
    <h2>Victor Crest <span class="card__age">26</span></h2>
    <p class="card__location">London</p>
  </div>
</div>
```
```css
.card {
  ...
}

.card__top-back {
  ...
}

.card__description {
  ...
}

.card__image {
  ...
}
```

### Continued development

I need to understand about using BEM.

### Useful resources

- [BEM](https://getbem.com) - one of the naming conventions


## Author

- Website - [github.com/mrMikHippo](https://github.com/mrMikHippo)
- Frontend Mentor - [@mrMikHippo](https://www.frontendmentor.io/profile/mrMikHippo)
