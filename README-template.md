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
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Screenshot](https://github.com/PiperRc/Profile-Card-Frontend-Mentor-/blob/main/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```


I was intially confused about how to make the background image. I knew about background-image, but I did not use it frequently. In the past, I had used the img tag on html. After doing research, I learn about the other properties, such as background-size, background-position and background-repeat. I will now be using background-image in the future
```css
 background-image: url('images/bg-pattern-top.svg'), url('images/bg-pattern-bottom.svg');
 background-repeat: no-repeat;
 background-position: right 42vw bottom 40vh, left 53vw top 40vh;
}
```
Also,I need to remeber to set the background color of the cards to white.
```
.card-1 {
    height: 40%;
    width: 100%;
    border: 1px solid grey;
    border-top-left-radius: 1rem;
    border-top-right-radius: 1rem;
    box-sizing: border-box;
    background-image: url('images/bg-pattern-card.svg');
    background-size: cover;
    background-color: white;
}
```


### Continued development
Need to do more research on background-position


### Useful resources

- [Mdn page on background position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position)-Helped me with background-position
- [CSS tricks page on background positon](https://css-tricks.com/almanac/properties/b/background-position/m) - Helped me with background-position


## Author


- Frontend Mentor - [@PiperRc](https://www.frontendmentor.io/profile/PiperRc)

