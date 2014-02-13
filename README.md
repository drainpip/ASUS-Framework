# ASUS Mobile Framework

A mobile-first framework for usage in ASUS' latest micro sites. This framework is heavily inspired by [twbs/bootstrap](https://github.com/twbs/bootstrap) as well as [zurb/foundation](https://github.com/zurb/foundation).

## Installation

We are currently using [gulp](http://gulpjs.com/) for our workflow. This will compile and minify all static files and output them into a folder for distribution.

To begin, you must install the dependencies if you haven't already.

* npm: http://npmjs.org/
* node.js: http://nodejs.org/download/

Once npm is installed get your cli up and running and install gulp: `npm install gulp -g`.

Fork this repo if you haven't already and `cd` into your local file where the `package.json` file is located in the root. From there, simply type: `npm install`. This will read the `package.json` file and download all the necessities.

Now that we're ready, you can start editing the `.scss` or `.js` files and simply type in `gulp` while sitting pretty in the working folder and it will build everything for you!

If you type in `gulp watch`, this will start up a static server at `localhost:5000` pointing to the dist folder. Make an index file, point to the css and you're off to the races.

This project is also using [LiveReload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en), so make sure that's ready too for awesome-sauce.