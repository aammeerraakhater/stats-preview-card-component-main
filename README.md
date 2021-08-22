# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents

  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)




### Links

- Solution URL: (https://6fxzvpvt0r66jj5ecjusug-on.drv.tw/WEB--Frontend%20Mentor/stats-preview-card-component-main/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

** To add the color on the images there 2 ways:
1--
Inside Html.
add div.layer inside the div.imgcontainer
Inside your css file.
 .layer {
    background-color: rgba(102, 25, 149, 0.5);
    position: relative;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
} 
converting site that helped me with this (https://convertingcolors.com/)
OR
2----much easier---
Inside your css file, inside your div.imgcontainer

    background-color: hsl(277, 64%, 61%);
    background-blend-mode:multiply; /*Can change the blend type if you want check this: (https://www.w3schools.com/cssref/pr_background-blend-mode.asp) */

--------------------------------------------------------------------------------------------------------------------
mediaQuery :
(https://www.w3schools.com/cssref/css3_pr_mediaquery.asp)
---------------------------------------------------------------------------------------------------------------------
to make variable out of color:

:root {
  --color-main-background: hsl(233, 47%, 7%);
  --color-card-background: hsl(244, 38%, 16%);
  --color-accent: hsl(277, 64%, 61%);
  --color-white-opaque: hsl(0, 0%, 100%);
  --color-white-transparent75: hsla(0, 0%, 100%, 0.75);
  --color-white-transparent60: hsla(0, 0%, 100%, 0.6);
}
-----------------------------------------------------
Thing that i forget about:
    text-align: center;
--------------------------------------------------
But how can i put the image first ?????
        flex-direction: column-reverse;
----------------------------------------------
borders?
- *
- *
- * * - border-radius: topLeft topRight bottomLeft bottomRight

### Continued development

margins and padding and font in this need some edits and adjustments
**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources
[mediaQuery] : (https://www.w3schools.com/cssref/css3_pr_mediaquery.asp) This helps me to change media styling
[convertingColorsType] (https://convertingcolors.com/) converting site that helped me with this 



## Acknowledgments

Got some help from this solution: 
https://github.com/chiptaylor/stats-preview-card-component
