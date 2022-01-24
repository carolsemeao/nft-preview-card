# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshots

![Mobile version](https://user-images.githubusercontent.com/82804218/150790760-ba31c447-3595-4cd1-bbcb-af6a918f8dd8.JPG)
![Desktop version](https://user-images.githubusercontent.com/82804218/150790128-27957be1-7847-4536-91e3-21b3d1c10d1e.png)

### Links

- Solution URL: [My solution](https://www.frontendmentor.io/solutions/nft-preview-card-component-8UAgHSfqN)
- Live Site URL: [NFT Preview Site](https://carolsemeao.github.io/nft-preview-card/)

## My process

### Built with

- HTML 5
- CSS custom properties
- Flexbox

### What I learned

I learned how to make multiple things change while hovering over one element. I'm very proud of my outcome

This is my code:
```
.card-img{
    position: relative;
	display: flex;
	align-items: center;
	overflow: hidden;
}

.card-img img{
    border-radius: 0.4rem;
}

.card-img #view{
    display: none;
    position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	z-index: 1;
    width: 3rem;
}

.card-img:hover, .card-img:active{
    cursor: pointer;
    background-color: var(--secondary-color);
    border-radius: 0.4rem;
}

.card-img:hover #view{
    display: block;
}

.card-img:hover #nft-pic{
    opacity: 0.5;
}

#nft-pic{
    border-radius:0.4rem;
    max-width: 100%;
}
```
### Useful resources

- [W3Schools](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Frontend Mentor Solutions](https://www.frontendmentor.io/solutions) - This was amazing to see, how many people have different solutions. After reading and finding the one that worked best for me, I analyzed their code and understood what I had to do
- [W3.org](https://www.w3.org/WAI/tutorials/images/) - This helped me to work on the alt texts for images

## Author

- Website - [NFT Preview Site](https://carolsemeao.github.io/nft-preview-card/)
- Frontend Mentor - [@carolsemeao](https://www.frontendmentor.io/profile/carolsemeao)
- Twitter - [@twiddyCodes](https://www.twitter.com/twiddyCodes)

## Acknowledgments

- [Quỳnh Giao](https://www.frontendmentor.io/profile/giaonnq1401) - Their provided code and the help in the comment section helped me out so much with making the eye icon appear in full opacity while hovering over the NFT image
- [Tymur Renhach](https://www.frontendmentor.io/profile/tymren608) - Their comment on my solution really helped me out with making my code easier to read. Thank you so much for the advise
