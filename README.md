# Handlebars Extensions

## Overview

The goal of this project is to develop a comprehensive, well documented and unit tested collection of commonly needed Handlebars.js helpers and extensions. Where possible, helpers will support both inline and block mode (read: inline if (iif) vs if/else blocks) which gives you greater flexibility when writing and structuring your templates.

### Dependencies

* [Handlerbars.js](http://handlebarsjs.com) v1.0.0
* [Lo-Dash](http://lodash.com/) v1.3.1

### Develpment Dependencies

A few notes if you are interested in contributing to the project or if you are just curious. Unit tests are written with the [Jasmine](https://jasmine.github.io/) framework (and its lovely BDD style syntax) and the project is configured to use the [Karma](http://karma-runner.github.io/) test runner to um... run them. Check out the *.spec.js files inside of the tests folder for more info.

To get started developing, clone the git repo to your local workspace and run:

    bower install

followed by:

    npm install

## Documentation

TODO: Working on how to best show the documentation in this page or in an external link.

Check out the code files in the src folder, each one of the helper methods has a documentation comment which includes a brief description and an example on how to use it.

## Changelog

v1.0.0

* Initial project load

v1.0.1

* Merged pull request that fixed context passing to block helper

v.1.1.0

* Minor project renaming
* Refactored to remove use of RequireJS module format, I figured that if you really need to convert this to an AMD module you can create a simple shim to include in your project
* Changed from the Jasmine HTML test runner to using Karma

## License

The MIT License (MIT)

Copyright (c) 2012 Fernando Berrios

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
