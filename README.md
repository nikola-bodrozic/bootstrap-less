# Boostrap Less Template with Boostrap select plugin

### Install
1. first run `npm install`
2. then `bower install`
3. build content of dist folder with `grunt` or `grunt dist`
4. optionally run local server `http-server -a localhost`

### Usage
 - HTML files are in root folder - index.html, login.html & reg.html
 - place Less files to `less/` or `less/mixins`
 - update `less/variables.less` and `less/minins.less`
 - add js file to `js/` folder an update concat.boostrp.src node in `gruntfile.js`
 - run grunt command `grunt dist` or `grunt`
 - copy files from `dist/` folder to production along with index.html
 - enjoy :)