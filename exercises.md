# Exercises

The following exercises should be worked on within the `exercise` folder. Only the CSS files need to be changed.

## Task 1 - Dark vs. Light!

This website is built with dark-mode as the default theme. However, some users might prefer light-mode. The goal of this exercise is to implement a light-mode for all those people.

Some tips:
- This project relies on CSS variables for its colors, check how you can change the variables if a user prefers light-mode
- Always remember to set your media-queries close to the concerning parts of your CSS
- Colors you can use for a light-mode: `#acacac`, `#b3b3ae`, `#f8f8f2`, `#282a36`

## Task 2 - Mobile vs. Tablet vs. Desktop

There are a lot of different screen sizes. This Exercise is built "mobile first" so go and develop the tablet (minimum width 600px) and desktop (minimum width 1000px) views! 

_Note: These are not necessarily appropriate breakpoints, they are for practice!_

1. On tablet, the articles should be in two columns, each coloumn should have the same width
2. On desktop, the articles should be in four columns, each column should have the same width
3. On tablet and desktop the icon of each article should be in the bottom right corner
4. Apply a responsive font-size and add variations for each type of device


## Task 3 - You can flip your phone! _(optional)_

You could catch the orientation change with the viewport-width, but there is also a way to directly notice a flipped phone. 

Try to implement a heart at the bottom right corner of the viewport which only appears if the media orientation is set to landscape. 

For this exercise you need to add another HTML element.

Some tips:
- You can build a heart by just using CSS, if you have time and energy give it a try!
