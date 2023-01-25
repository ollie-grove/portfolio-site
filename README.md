# portfolio-site
My portfolio site! 
# README template from FrontendMentor

## Table of contents

## Overview
I wanted to redesign my portfolio! 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

Before:

And After!:

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I researched some upcoming 2023 web design trends, and decided to go with a Glassmorphism design. After spending some time on Pinterest looking at different color schemes, I decided to do a light and dark theme, and started coding the dark theme first.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

- When changing from hex to HSL in VSCode, just hover over the color box and click on the top bar. I was Googling HSL to HEX🫡
- Accessbility: 
  - em-based breakpoints work best across all browsers
  
- Using modern fluid typography with CSS function clamp(). Fluid typography changes with the user's screen size, whereas responsive typography changes with media queries

- Comment shortcuts: To comment out a block of code, select the code you want to comment out and hit CTRL + /. Similarly, to add a comment, place cursor where you want the comment to start and hit the same shortcut. 

- Device Pixel Ratio (DPR) or CSS Pixel Ratio: "...ratio between physical pixels (screen size or resolution) and CSS pixels (viewport. Depending on device specification, one CSS pixel can equal one or more physical pixels. Modern devices have screens with high pixel density resulting in the difference between screen size (resolution) and viewport." Viewport: number of software (CSS) pixel present on a screen. 
  - Summary: 
    - Screen size (Resolution) = viewport size x Device Pixel Ration
    - Viewport size = Screen size / Device Pixel Ratio
    - CSS pixel ratio = Screen size / viewport size
(https://blisk.io/devices/details/iphone-12)

To see how you can add code snippets, see below:

```<h1 class="hero-headline">
            Hi, I'm <span>Ollie Grove.</span>
          </h1>
```
```h1 span {
    background-image: linear-gradient(to right, var(--accent) 75%, var(--accent) 75%);
    background-position: 0 1.218em;
    background-repeat: repeat-x;
    background-size: 8px 4px;
}

//From (https://codepen.io/johndjameson/pen/NrZgQY)
What this does: Use a background image and linear gradient (in this case to the same color) to add an underline to text. You can control the space in between the line and the text and thickness/decoration of the text. And it works even if the line breaks. 
```
```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [The Clamp Calculator](https://royalfig.github.io/fluid-typography-calculator/) - This website allows you to input font sizes and viewports of your project, and creats a CSS clamp property with fallback.
- [Easy Fluid Typography by Ryan Feigenbaum](https://ryanfeigenbaum.com/fluid-typography/) - "Fluid typography is text that scales in size and proportion to the user's viewport. ...font size should decrease as the screen becomes smaller and increase as it becomes larger." "Responsive typography works by changing font size via media queries." 
- [PX, EM, or REM Media Queries? by Zell Liew](https://zellwk.com/blog/media-query-units/) - Helps explain why em-based media queries are best for accessibility. My takeaway is that is helps to support users who change their browser's font-size value. Using pixels for smaller spacing (like between social media icons) is okay. 
- [Accessibility Developer Guide](https://www.accessibility-developer-guide.com/) - Helpful for creating websites that are navigable for people using screen readers or without using a mouse.
- - [fffuel](https://fffuel.co/)) - Fun, free website for free SVG generators. You can make gradients, patterns, textures, shapes, and backgrounds. This is the site I used to create the background shapes in my portfolio. 

## Acknowledgments

Coder Coder on YouTube (https://www.youtube.com/@TheCoderCoder) - I watched a code-along video of a single-page developer portfolio challenge from Frontend Mentor. I learned SO MUCH just by watching Jess's Process. She is very mindful about accessbility. Several of the #Useful Resources are links that she recommended. 

