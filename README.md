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
- [Acknowledgments](#acknowledgments)

## Overview

This challenge requires us to build a responsive card component that stacks on
smaller screeen sizes while flattening out horizontally on bigger ones. No JS is required, this
is a pure HTML and CSS project.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- Images should be responsive i.e. smaller image for small screens, larger one for
  larger screens.

### Screenshot

![](./design/my-result.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

First I deduced the optimal HTML structure for the card (which I updated as
I carried on and met some overlooked nuances) that is both semantic(-ish) and provides
hooks for CSS styling.  
Then I devised all the necessary CSS variables and defaults (I didn't
bother importing any 3rd party resets, I just made the ones I needed for headings and paragraphs).  
After that I did the mobile layout first - starting with major layout, image
styles and then gradually going top-down and tweaking some spacing and font-sizes.  
Afterwards I repeated the same process for the desktop layout, this time spending less
for devising the layout and more on tweaking the spacing and font sizing. Getting the card image
to display with the correct purple hue was tiresome, so I just tried to get it as similar
as possible without obsessing too much about it.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- BEM naming system
- Mobile-first workflow

### What I learned

I should probably spend more time researching the HTML structure and its alternatives,
extrapolated from how the responsive structure changes going from mobile to desktop, and
pay more attention to smaller details.
Usual image quirks popped up (like the phantom space that needs to be dealt with
using `vertical-align: bottom` hack).
Also using the `<picture>` element with `<source>` + default `<img>` was something I
knew about but never really tried before.

### Continued development

Going forward I think I'll do more research on extrinsic vs intrinsic CSS sizing and more
on responsive images, since I left like I'm doing a little too much ad-hoc styling.

## Author

- Frontend Mentor - [@marisudris](https://www.frontendmentor.io/profile/marisudris)
- GitHub - [@marisudris](https://www.github.com/marisudris)
