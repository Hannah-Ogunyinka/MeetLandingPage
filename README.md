# MeetLandingPage
Frontend Mentor challenge
# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Meet landing page solution](#frontend-mentor---meet-landing-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshots](#screenshots)
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
- See hover states for interactive elements

### Screenshots

![](./Screenshots/Desktop-view-1440px-width.png)

![](./Screenshots/Tablet-view-700px.png)

![](./Screenshots/Mobile-view-375px-wide.png)


### Links

- Live Site URL: [Meet Landing Page](https://hannah-ogunyinka.github.io/MeetLandingPage/)

## My process

Initially, I built the HTML file only considering the order I wanted the items to be in. I already had an understanding of some basic elements such as how to structure the head and body ,however after pausing the project for a time to learn flexbox and CSS grid, I improved the structure with these elements in mind.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned
As mentioned in my process above, I had to pause and learn CSS grid and flexbox.  I have used Bootstrap in the past but wanted to use an approach that didn't rely on frameworks.

I also had to learn:
- How to reset all elements of a page with *;
- How to hide parts of an image with 'overflow:hidden";
- How to overlay images;
- And use the 'white-space' attribute.

I was particularly proud of the code below, since I was essentially drawing with css which I'd never done before.


```html
  <div class="number-one-icon">
      <div class ="container">
        <div class="vertical-line"></div>
        <div class="number-one-circle">
          <div class="number"><p>01</p></div>
        </div>
      </div>
```
```css
.proud-of-this-css {
 .number-one-icon {
    height: 300px;
    display: flex;
    align-items: center;
}

.number-one-icon .container{
    display: grid;
    grid-template-columns: repeat(12, 1fr);
    grid-template-rows: 1fr 1fr;
    
}

.vertical-line  {
    border-right: 0.5px solid #87879D;
    height: 84px;
    grid-column: 1/ 7;
    grid-row: 1/ 2;
}

.number-one-circle {
    grid-column: 1/ 13;
    grid-row: 2 /3; 
    justify-self: center;
    left: -1px;
    display: flex;
    border: 0.5px solid #87879D;
    font-weight: bold;
    height: 50px;
    width: 50px;
    border-radius: 100%;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    font-size: 16px;
    right: 10px;
    background-color: #fafafa;
}
}
```

### Continued development

And is apparent in the desktop screenshot, there is margin gap on either side of the intro images which I couldn't remove.  I know this is related to how I structured my containers.  Even after tying to troubleshoot with Firefox, i couldn't remove this margin.  I will continue to develop my using of flexbox and positioning.

### Useful resources

- [Scrimba learning - CSS grid](https://scrimba.com/learn/cssgrid/) - This was a helpful introduction to how CSS grid works.
- [css-tricks website for flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is helpful as it broke down all the flexbox attributes in a clear and simple way.
- Stack Overflow was also helpful. Nothing is new under the sun so there were answers to questions there that didn't require me to ask directly.


## Author

- Twitter - [@Hannah_2004](https://twitter.com/Hannah_2004)

