# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

- This is my first ever Front End Mentor project and I chose Nft card component challenge for this.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In this project I've learned the html semantics and how to show an item on hover using opacity only.

```html
<article class="main-image">
  <img src="images/image-equilibrium.jpg" alt="Equilibrium Image" />
  <div>
    <img src="images/icon-view.svg" alt="" />
  </div>
</article>
<article>
  <h2>Equilibrium #3429</h2>
</article>
```

```css
.container .main-image div {
  position: absolute;
  cursor: pointer;
  top: 0;
  width: 100%;
  height: calc(100% - 4px);
  /* text-align: center; */
  background-color: hsla(178, 100%, 50%, 0.5);
  border-radius: 10px;
  z-index: 999;
  opacity: 0;
  transition: all 0.3s ease-in;
}
.container .main-image div img {
  position: absolute;
  top: 37%;
  left: 50%;
  transform: translate(-50%, 50%);
}
.container .main-image div:hover {
  opacity: 1;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

-- Needs to work on html semantics, as I've found out that it makes the code clean and also less amendmends needed in design.

-- Needs to work on transform: translate() property to fully understand the concept

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.youtube.com/watch?v=9bGbykdR4T8) - This video helped me in html semantics. I really liked this pattern and will use his methods in future projects.
- [Example resource 2](https://www.w3shools.com) - This website helped in understanding the html concepts very easily.

## Author

- Website - [Imran](https://meetimran.netlify.app/)
- Frontend Mentor - [@emraan07](https://www.frontendmentor.io/profile/emraan07)
- Twitter - [@yourusername](https://twitter.com/codewithimran)
