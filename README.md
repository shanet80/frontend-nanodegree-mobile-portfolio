Website Performance Optimization Project

To run this application: 1. Download or clone this repository to your computer. 2. Open the files on your localhost.

Index.html is optimized to a PageSpeed score above a 90 by: 1. Inlining critical pass css with the help of http://jonassebastianohlsson.com/criticalpathcssgenerator/ 2. Resize and compressing images with the help of https://compressor.io/ 3. Minifying css with the help of Atom package Minify.

Pizza.html is optimized to 60fps by 1. Setting 3 sizes for the changePizzaSizes function rather than calculating them 2. Instead of creating 200 pizzas for movingPizzas1, 30 are created because not all 200 are displayed on screen at once. 3. Use getElementsByClassName() instead of querySelectorAll() in changePizzaSizes and removed from for loop
