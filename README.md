## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

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

