# Starter kit to use Gulp with Less.
====================================
A super clean and easy to use starter kit for using Gulp and Less. This should help you repurpose Gulp and Less for your own projects.

- Read the article: : http://scotch.io/tutorials/getting-started-with-less
- Watch the video: https://www.youtube.com/watch?v=5nqWhwsMQqs

## Features

### LESS / CSS Stuff

- Watches for Less changes on save
- Checks for Less errors and outputs them without you having to rerun Gulp
- Autoprefixes for legacy browsers
- Combines all CSS into one big and sexy minified file
- Includes Less Bootstrap

### Javascript Stuff

- Lints custom scripts for errors
- Combines all custom scripts into one file

## How To Use

    $ git clone git@github.com:abruzzi/gulp-and-less-starter-kit.git
    $ cd gulp-and-less-starter-kit
    $ npm install
    
After, run

    $ gulp
    
...if you need a local server. Folder **build** serving at [http://localhost:8100](http://localhost:8100)

Should use [Livereload extension](http://livereload.com/extensions/). Or inject `<script src="//localhost:35729/livereload.js"></script>` into your page.

When you change a LESS(or JS) file, the page will reload.

## Quick Tips
- Any changes in `assets/less/*` will trigger the Less to compile on save
- All files in `assets/js/libs/*`  will be compressed to `build/jquery.plugins.min.js`
- All files in `assets/js/*` (except for `libs`) will be compressed to `build/scripts.min.js`


#### Special Thanks

-  To Kenny Song for his contributions and [site](https://github.com/baivong)
-  To Scotch for the original starter kit and [article](https://scotch.io/tutorials/a-quick-guide-to-using-livereload-with-gulp)