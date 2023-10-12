# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/profile-card-website-mKvyYR7QRw)
- Live Site URL: [Add live site URL here](https://ashraful-fuqha.github.io/profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Animation and Transition

### What I learned

Learned about the Animation part of CSS3 and practiced media break-points.

see below:

```html
<section class="insight">
        <div class="Followers">
          <h2>80K</h2>
          <p>Followers</p>
        </div>
        <div class="Likes">
          <h2>803K</h2>
          <p>Likes</p>
        </div>
        <div class="photos">
          <h2>1.4K</h2>
          <p>Photos</p>
        </div>
      </section>
```
```css
@keyframes introLoad {
    0%{
        transform: translateX(-10rem);
        opacity: 0;
    }
    100%{
        transform: translateX(0);
        opacity: 1;
    }
}

/* Breakpoints Section */

@media only screen and (min-width:376px) {
    main{
        background-position: left -20vw bottom 45vh, right -20vw top 45vh;
    }

}
```

### Continued development

I'm using SCSS pre-processor in the next part.

## Author

- Website - Defnitely
- Frontend Mentor - [@MjafarsadiqD](https://www.frontendmentor.io/profile/Ashraful-Fuqha)