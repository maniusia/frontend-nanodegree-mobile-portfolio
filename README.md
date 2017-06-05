# Web Optimization

## Project Objective:

 Optimize a provided website with a number of optimization- and performance-related issues so that it achieves a target PageSpeed score and runs at 60 frames per second.

## Running Instruction: 
 
 1.	Copy the link to the portfolio page: https://maniusia.github.io/frontend-nanodegree-mobile-portfolio/views/pizza.html
 2.	Go to https://developers.google.com/speed/pagespeed/insights/ and paste the portfolio page url in the window with: Enter a web page URL.
 3. Click on Analyze
 4. Open the portfolio page in the browser.
 5. Open DevTools 
 6. Refresh the page and read the output in DevTools in the Performance tab.
 

## Optimizations performed:
### Index.html / pizza.html

1. Asynced the Analytics script.
2. Inlined and minified the style.css.
3. Added media query to the print stylesheet.
4. Moved scripts, font link and print stylesheet to the bottom of the pizza.html.
5. Optimised images using  (http://optimizilla.com/)

### main.js

1. Fixed the Pizza Sizer function by moving var outside the loop and simplified the for loop. Changed the switch statement.
2. Fixed the Scroll function by creating and moving the var outside the loop and changing amount of appearing pizzas.  
