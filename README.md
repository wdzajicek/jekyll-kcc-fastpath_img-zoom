# KCC Fast Path

## Landing Page for the KCC Fast Path Program

### <a href="https://kankakeecommunitycollege.github.io/jekyll-kcc-fastpath/" target="_blank" rel="noopener">Link to github-page for Fast Path <br /> https://kankakeecommunitycollege.github.io/jekyll-kcc-fastpath/</a>

<img src="assets/img/fastpath-example.jpg">

Adapted from ShakyShane's jekyll-gulp-sass-browser-sync starter project. He did the initial setup for Jekyll, GulpJS, SASS, AutoPrefixer &amp; BrowserSync. I added gulp-cssmin and modified the gulpfile.js to create 2 versions of the css style sheet: main.css and the style sheet the production-site links to main.min.css

ShakyShane - https://github.com/shakyShane
ShakyShane's jekyll-gulp-sass-browser-sync repo - https://github.com/shakyShane/jekyll-gulp-sass-browser-sync

## System Preparation

To use this starter project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)
4. [gulp-cssmin](https://www.npmjs.com/package/gulp-cssmin) - install node_module with `$ npm install --save-dev gulp-cssmin`

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

```shell
$ gulp
```

**jekyll**

As this is just a Jekyll project, you can use any of the commands listed in their [docs](http://jekyllrb.com/docs/usage/)

## Deploy with Gulp

You can easily deploy your site build to a gh-pages branch. First, follow the instructions at [gulp-gh-pages](https://github.com/rowoot/gulp-gh-pages) to get your branch prepared for the deployment and to install the module. Then, in `gulpfile.js` you'll want to include something like the code below. `gulp.src()` needs to be the path to your final site folder, which by default will be `_site`. If you change the `destination` in your `_config.yml` file, be sure to reflect that in your gulpfile.
