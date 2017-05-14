[<img src="https://github.com/pixelminds/bourbonpug/blob/master/bourbonpug_logo.png" alt="Bourbonpug logo">](https://github.com/pixelminds/bourbonpug)

# bourbonpug
[![Release v1.0](https://img.shields.io/badge/release-v1.0.125-orange.svg)](https://github.com/pixelminds/bourbonpug) [![Bourbon v5.0.0 b7](https://img.shields.io/badge/bourbon-v5.0.0%20b7-red.svg)](http://bourbon.io/) [![Neat v1.8.0](https://img.shields.io/badge/neat-v1.8.0-blue.svg)](https://github.com/thoughtbot/neat/tree/neat-1.8.0-node-sass) [![jQuery v3.2.1](https://img.shields.io/badge/jquery-v3.2.1-green.svg)](https://jquery.com/) [![GPLv3 license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.txt) 

**Bourbonpug** is an opinionated template or boilerplate you can use as a starter for small static multipage websites. We included popular effects such as parallax images or sticky navigation, which you can of course use or not. As a core framework we used Bourbon, Neat, Bitters and Refills, which rely on JQuery for some dynamic behaviors. 
### Preprocessor and templating engine
Editing in HTML and CSS would be specially tough without a template engine and a CSS preprocessor. In this project we rely on Jade and SASS. Jade is now called Pug, so now you know where we made the project name up from. By using mixins, nesting & variables in CSS and dry syntax with partials for the HTML structure, productivity is greatly enhanced. Despite this belief, we've had a bad experience with workflow or dependency managers based on node.js (gulp, grunt, bower), and we can't use solutions based in Ruby, because Windows is not Ruby-friendly. Our best candidate for processing is Prepros, so we included the Prepros config file.

Jade is very helpful in drying the HTML syntax, but its real power arises when you use it as a templating language. In this project we've only used the partials feature, allowing us to write repetitive parts only once (header, footer). Slim is another cool templating language, which many consider still dryer than Jade, plus it uses Ruby (just like SASS). But the include plugin is not working by default on Prepros, so I'm sticking to Jade.
### CSS Maintainability
New in version 1.0.1 - CSS maintainability is managed by layering all the SCSS in logical groups. We tried to follow standards like SMACSS or ITCSS, but they didn't quite match our needs. We thought this project was small enough, and we wanted to feel confortable, so we made up our own file structure: resets > variables > layout > tools > elements > theme. Each of these groups could match one or other category in the methods mentioned above, but we found ourselves somewhere in between.

Regarding the naming conventions, and selector-level maintainability, since we're basically reusing existing components and resources, we decided not to tackle this issue, and leave all classes untouched. This is also important in the evetual case of upgrading part of the third party code. Moreover, we prefer keeping HTML as dry as possible, as semantic as possible (no classitis, no divitis), despite the widespread opinion that the best practice in CSS is to watch over specificity issues and to avoid tag selectors.
### Installation
Simply download **Bourbonpug** and drop the folder onto Prepros. 
### Usage
Any changes made to Jade or SCSS documents will be processed into HTML/CSS.
### Tools and resources used
* [**Prepros**](https://prepros.io/) by [Subash Pathak](https://github.com/Subash) for SASS / Jade preprocessing.
* [**Initializr**](http://www.initializr.com/) by [Jonathan Verrecchia](http://verekia.com/) for the boilerplate essentials. Including [HTML5 Boilerplate](https://html5boilerplate.com/) v5.0 by the [H5BP Team](https://github.com/h5bp).
* [**Bourbon**](http://bourbon.io) - Thanks to the design team at [Thoughtbot](http://thoughtbot.com/) for the Bourbon ecosystem.
  * [Bourbon](https://github.com/thoughtbot/bourbon) v5.0.0 b7 - SASS mixins for fast prototyping.
  * [Neat](https://github.com/thoughtbot/neat) v1.8.0 - Semantic grid for use with Bourbon. Must use v. 1.8.0 (refills will not work with Neat v2).
  * [Bitters](https://github.com/thoughtbot/bitters) v1.5.0 - base SASS variable set.
  * [Refills](http://refills.bourbon.io/) - Patterns and components (requires Bourbon + Neat). Used: cards, navigation, type system, footer.
* [**JQuery**](https://code.jquery.com/jquery-3.2.1.min.js) v3.2.1 by John Resig and the [JQuery Foundation](https://jquery.org/team/) - JQuery plugins:
  * [Parallax.js](http://pixelcog.github.io/parallax.js/) v1.4.2 by [PixelCog Inc.](http://pixelcog.com/about/) for the parallax effect.
  * [Sticky.js](http://stickyjs.com/) v1.0.4 by [Anthony Garand](http://anthonygarand.com/) for the sticky navigation bar.
* Web resources:
  * [**HTML 2 Jade**](http://html2jade.org/) for the HTML > Jade(Pug) translation.
  * [**Lorempixel**](http://lorempixel.com/) for the placeholder images.
  * [**LatLong**](http://www.latlong.net/) for the map coordinate calculation.
  * [**W3 Schools**](https://www.w3schools.com/icons/default.asp) for the social icon procedure.
