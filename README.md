# Frontend Mentor - NFT preview card component solution by Jorge H. Guzmán J.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./solution/Screenshot1.png)
![](./solution/Screenshot2.png)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: [FrontEnd Mentor: My Solution](https://www.frontendmentor.io/solutions/nft-preview-card-component-solution-by-jorge-h-guzmn-j-Fwax2nP7s)
- Live Site URL: [GitHub Page: NFT Card Solution](https://jhguzmanj.github.io/Challenge2/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

I have learned about handling :root to store information for later use.

```css
:root {
  --Soft-blue: hsl(215, 51%, 70%);
  --Cyan: hsl(178, 100%, 50%);
  --Very-dark-blue-mainBG: hsl(217, 54%, 11%);
  --Very-dark-blue-cardBG: hsl(216, 50%, 16%);
  --Very-dark-blue-line: hsl(215, 32%, 27%);
  --White: hsl(0, 0%, 100%);
}

Also about the display option:

.main {
  margin: 24px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

And finally, how to adjust sizes of images, texts and boxes according to the size of the screen:

@media (max-width: 378px) {
    section {
        width: 325px;
        height: 550px;
    }

### Continued development

In the future, my goal is:
- learn the property of position in more depth
- better organize html
- use css grid

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow) - This helped me with the box shadow property.
- [CCS Web Docs](https://devdocs.io/css/display) - This helped me with the display property.

## Author

- Website - [Jorge H. Guzmán J.](https://www.jhguzmanj.com) *I plan to create it later.*
- Frontend Mentor - [@jhguzmanj](https://www.frontendmentor.io/profile/jhguzmanj)
- GitHub - [jhguzmanj](https://github.com/jhguzmanj)
