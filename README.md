README #
---

#Node.js and NPM
If you don't have Node.js and NPM installed you can download them here: [https://nodejs.org/en/](https://nodejs.org/en/)

You will only need to install this once and they will be installed system wide.  NPM is installed as part of Node.js so you should only need the one download.

#Initializing

If you need to do a global install of gulp type __npm install -g gulp__

Navigate to the project folder in Terminal and type __npm install__.  This will install all the packages listed below.

##Gulp
*Task automation tool*

[https://www.npmjs.com/package/gulp](https://www.npmjs.com/package/gulp)

# Gulp Plugins

## gulp-eslint
*Validates JavaScript*

[https://www.npmjs.com/package/gulp-eslint](https://www.npmjs.com/package/gulp-eslint)

## jshint-stylish
*Formats jshint error messages for easier readability with color coding and icons*

[https://www.npmjs.com/package/jshint-stylish](https://www.npmjs.com/package/jshint-stylish)

## gulp-htmlhint
*Validates HTML*

[https://www.npmjs.com/package/gulp-htmlhint](https://www.npmjs.com/package/gulp-htmlhint)

## htmlhint-stylish
*Formats htmlhint error messages for easier readability with color coding and icons*

[https://www.npmjs.com/package/htmlhint-stylish](https://www.npmjs.com/package/htmlhint-stylish)

## gulp-sass
*Compiles SASS*

[https://www.npmjs.com/package/gulp-sass](https://www.npmjs.com/package/gulp-sass)

## gulp-autoprefixer
*Automatically add vendor prefixes to css properties*

[https://www.npmjs.com/package/gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)

## gulp-useref
*Parse build blocks in HTML files to replace references to non-optimized scripts or stylesheets*

[https://www.npmjs.com/package/gulp-useref](https://www.npmjs.com/package/gulp-useref)

## gulp-uglify
*Minify JavaScript*

[https://www.npmjs.com/package/gulp-uglify](https://www.npmjs.com/package/gulp-uglify)

## gulp-if
*Add conditional statements to gulp tasks*

[https://www.npmjs.com/package/gulp-if](https://www.npmjs.com/package/gulp-if)

## gulp-concat
*Concatenate files*

[https://www.npmjs.com/package/gulp-concat](https://www.npmjs.com/package/gulp-concat)

## gulp-cssnano
*Minify CSS*

[https://www.npmjs.com/package/gulp-cssnano](https://www.npmjs.com/package/gulp-cssnano)

## gulp-imagemin
*Minify PNG, JPEG, GIF and SVG images*

[https://www.npmjs.com/package/gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)

## gulp-cache
*Cache task results to save time on future builds*

[https://www.npmjs.com/package/gulp-cache](https://www.npmjs.com/package/gulp-cache)

## del
*Delete files and folders*

[https://www.npmjs.com/package/del](https://www.npmjs.com/package/del)

## gulp-sourcemaps
*Generate sourcemaps for minified and concatenated files*

[https://www.npmjs.com/package/gulp-sourcemaps](https://www.npmjs.com/package/gulp-sourcemaps)

## gulp-plumber
*Gracefully handle errors in the pipeline without killing watch tasks*

[https://www.npmjs.com/package/gulp-plumber](https://www.npmjs.com/package/gulp-plumber)

## gulp-notify
*Display error messages in the console from the plumber task*

[https://www.npmjs.com/package/gulp-notify](https://www.npmjs.com/package/gulp-notify)

---
# Available Gulp Tasks
*Any of these can be called in the terminal by typing "__gulp {task name}__", for example the css task could be called by typing "__gulp css__"*

## scripts
*Calls the __jsHint__ then __jsMinify__ tasks in that order*

Use "__gulp scripts__" to call this task.

## styles
*Calls the __sass__ then __css__ tasks in that order*

Use "__gulp styles__" to call this task.

## watch
*Monitors all html, javascript, css and sass files for changes and automatically calls the __pages__, __styles__ and __scripts__ tasks as needed*

Use "__gulp watch__" to call this task.

## pages
*Calls the __htmlHint__ then __copyPages__ tasks in that order*

Use "__gulp pages__" to call this task.

## build
*Calls the tasks in this order __clean:build__, __sass__, __css__, __scripts__, __images__, __fonts__, __media__, __pages__*

Use "__gulp build__" to call this task.
