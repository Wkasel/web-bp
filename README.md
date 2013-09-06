# README
-----
Template

## stack
-----
Made with v 0.1 of Medley by William Kasel
Layout: Bootstrap 3.0.0
Templates: Jade
css: Less
JS: Coffeescript -- JQuery

## Getting Started
-----
### Static Route
You DO NOT have to use the pre-compilers, you can actually edit the css, javascript, and html manually if you like, however, if you do this, do not run the build script, otherwise it will overwrite any changes you make.
### Dynamic Route
Ensure you have installed [Node](nodejs.org) & [NPM](https://npmjs.org/), otherwise you won't be able to compile anything. Ensure you have [grunt](https://github.com/gruntjs/grunt/) installed as well. It makes your life much easier with the pre-compilers. Also, as of this writing, we depend on the 0.4.0 version of Grunt, so some grunt plugins won't work because they changed a ton of things. 

_On first install:_

  `cd js/build && (sudo) npm install`

Once you're ready done with the initial setup, you will be able to do the following:
  
  `grunt watch`
  
That's it! It will compile the Coffeescript, Less, Jade, and generated JS from Coffeescript, plus it concat's, uglifies, and gzips!

*Javascript -> [coffeescript](js/coffee)
*Templates -> [jade](templates/jade) (compiles to /static (handlebars))
*CSS -> [less](css/less)