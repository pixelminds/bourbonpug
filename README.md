[<img src="https://github.com/pixelminds/bourbonpug/blob/master/bourbonpug_logo.png" alt="Bourbonpug logo">](https://github.com/pixelminds/bourbonpug)

# bourbonpug
**Bourbonpug** is an opinionated template or boilerplate you can use as a starter for small static multipage websites. We included popular effects such as parallax images or sticky navigation, which you can of course use or not. As a core framework we used Bourbon, Neat, Bitters and Refills, which rely on JQuery for some dynamic behaviors. 

Editing in HTML and CSS would be specially tough without a template engine and a CSS preprocessor. In this project we rely on Jade and SASS. Jade is now called Pug, so now you know where we made the project name up from. By using mixins, nesting & variables in CSS and dry syntax with partials for the HTML structure, productivity is greatly enhanced. Despite this belief, we've had a bad experience with workflow or dependency managers based on node.js (gulp, grunt, bower), and we can't use solutions based in Ruby, because Windows is not Ruby-friendly. Our best candidate for processing is Prepros, so we included the Prepros config file.

Jade is very helpful in drying the HTML syntax, but its real power arises when you use it as a templating language. In this project we've only used the partials feature, allowing us to write repetitive parts only once (header, footer).

Installation: simply download **Bourbonpug** and drop the folder onto Prepros. 

Usage: Any changes made to Jade or SCSS documents will be processed into HTML/CSS.

Tools and resources used:

* [**Prepros**](https://prepros.io/) by [Subash Pathak](https://github.com/Subash) for SASS / Jade preprocessing.
* [**Initializr**](http://www.initializr.com/) by [Jonathan Verrecchia](http://verekia.com/) for the boilerplate essentials.
* [**Bourbon**](http://bourbon.io) - Thanks to the design team at [Thoughtbot](http://thoughtbot.com/) for the Bourbon ecosystem.
  * [Bourbon](https://github.com/thoughtbot/bourbon) - SASS mixins for fast prototyping.
  * [Neat](https://github.com/thoughtbot/neat) - Semantic grid for use with Bourbon. Must use v. 1.8.0 (refills will not work with Neat v2).
  * [Bitters](https://github.com/thoughtbot/bitters) - base SASS variable set.
  * [Refills](http://refills.bourbon.io/) - Patterns and components (requires Bourbon+Neat). Used: cards, navigation, type system, footer.
* [**JQuery** CDN](https://code.jquery.com/jquery-3.2.1.min.js) by John Resig and the [JQuery Foundation](https://jquery.org/team/) - JQuery plugins:
  * [Parallax.js](http://pixelcog.github.io/parallax.js/) by [PixelCog Inc.](http://pixelcog.com/about/) for the parallax effect.
  * [Sticky.js](http://stickyjs.com/) by [Anthony Garand](http://anthonygarand.com/) for the sticky navigation bar.
* Web resources:
  * [**HTML 2 Jade**](http://html2jade.org/) for the HTML > Jade(Pug) translation.
  * [**Lorempixel**](http://lorempixel.com/) for the placeholder images.
  * [**LatLong**](http://www.latlong.net/) for the map coordinate calculation.
  * [**W3 Schools**](https://www.w3schools.com/icons/default.asp) for the social icon procedure.
