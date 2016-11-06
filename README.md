## Website Performance Optimization portfolio project

My challenge was to optimize [this online portfolio](https://github.com/udacity/frontend-nanodegree-mobile-portfolio) for speed! In particular, optimizing the critical rendering path and make this page render as quickly as possible by applying the techniques I've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

##Running

Check out or download the code and click on index.html to open

## Improvements Made

####index.html

View changes without minification at index.original.html

* Inline CSS
* Inline Google fonts
* Inline JavaScript
* Set analytics to async
* Optimise profile pic using Gimp
* Optimise and make small version of pizzeria using Gimp
* Minify index.html

####views/js/main.js

* 424: removeDetermineDX function and integrate functionality with changePizzaSizes
* 444: only calculate container size for one pizza since all pizzas are the same size
* 501: moved phase calculation outside the loop. This gets rid of Forced Reflow issue
* 528: reduced number of pizzas, thereby less items to animate when scrolling

