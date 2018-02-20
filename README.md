# mysql-orm
The node.js ORM for MySQL 


### Building ###

The library uses [grunt](http://gruntjs.com/) for building. Alternatively, you can download the latest build from [here](https://github.com/niklasvh/html2canvas/blob/master/dist/html2canvas.js).

Clone git repository with submodules:

    $ git clone --recursive git://github.com/niklasvh/html2canvas.git

Install Grunt and uglifyjs:

    $ npm install -g grunt-cli uglify-js

Run the full build process (including lint, qunit and webdriver tests):

    $ grunt

Skip lint and tests and simply build from source:

    $ grunt build
    

### Contributing ###

If you wish to contribute to the project, please send the pull requests to the develop branch. Before submitting any changes, try and test that the changes work with all the support browsers. If some CSS property isn't supported or is incomplete, please create appropriate tests for it as well before submitting any code changes.
