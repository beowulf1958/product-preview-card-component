# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
including see the image swap between desktop and mobile version.
- See hover and focus states for interactive elements

### Screenshot

![Screenshot](/images/Web%20capture_20-6-2024_16325_.jpeg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Sass / scss


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

This was my second go at this project. My goal was to complete this quickly using Sass. The project took longer than expected because I could not get the images to come out right. The first time I did this project I used picture element, but the image was shorter than the card content. I tried to use sourceset with img, but that didin't work. Finally looked at other solutions and settled on the one  @MatthewPCope used with a background-image on a div. Worked fine.

There was some challenges using flexbox on the card content, so I switched to grid

To see how you can add code snippets, see below:


```css
.img-container {
  background-image: url(images/image-product-desktop.jpg);
  background-size: cover;
  min-height: 20rem;
  border-radius: 10px 0 0 10px;
}
```


### Continued development

Continuing to learn more about Sass, including min-ins and functions. Will return to image swapping with <picture> and img sourceset.

### Useful resources

- [Resource 1](https://www.sololearn.com/en/Discuss/1701930/what-is-the-difference-between-s-and-del-) - This helped me understand the difference between <s> and <del>. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@beowulf1958](https://www.frontendmentor.io/profile/@beowulf1958)


## Acknowledgments

Shout out to @sara11211 for her beautiful web page. I found it very inspiring and loved her use of BEM naming convention. I copied her class names very closely. She also pointed out the <s> tag to me; I did a little research and learned the semantic mening of the tag.

I would also like to mention @MatthewPCope for giving me the clue to use grid to switch, as well as using <div> with background-image to swap the jpgs.
