# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Live Site URL: https://vercel.com/new/success?developer-id=&external-id=&redirect-url=&branch=master&deploymentUrl=huddle-landing-rg486h6nv-nyakita.vercel.app&projectName=huddle-landing

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use rem and em for font-size, padding and margin. I used to avoid width and height setup in px or any other units except for percentage.
Also I finally started doing layout using grid. 
To see how you can add code snippets, see below:
```css
.wrapper{
  display:grid;
  grid-template-columns:1fr .7fr;
  grid-template-rows:15em 20em 10em;
  grid-template-areas:
  "item1 ."
  "item2 item3"
  "item4 item4";
  grid-gap:2em;
  width:100%;
}
```

I recommend to watch this guy: https://www.youtube.com/kepowob. He is really gik to CSS responsiveness, plus he explains everything the way you will understand.


