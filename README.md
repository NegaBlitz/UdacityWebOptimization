# Website Optimization
This project is a portfolio that was optimized to run much more smoothly. Contained are two main files, the ```index.html``` and ```views/pizza.html``` files. Viewing them is as simple as right-clicking and opening them in the browser of your choice.

## index.HTML and the Portfolio
The portfolio has a PSI (Page Speed Insights) score of at least 90 on both mobile and desktop.

##### Changes include:
* Inlined CSS and Javascript
* Optimized images via grunt
* Minimized Javascript and Minimized HTML
* Removal of the web-font (Open-Sans is already a default font)
* Addition of 'media="print"' next to the print.css call.
* Made the external analytics.js file by google asynchronous.

The image optimizations made the biggest difference, but these were the changes made.

## pizza.html and main.js
Most of the fixes here were weeding out asynchronous layouts from the ```resizePizzas()``` and ```updatePositions()``` functions. I also removed an unnecessary function and followed along with the videos to make the scrolling smoother (though the site is still pretty hard on the eyes).