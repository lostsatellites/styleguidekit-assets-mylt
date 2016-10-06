![license](https://img.shields.io/github/license/pattern-lab/styleguidekit-assets-default.svg)
[![Packagist](https://img.shields.io/packagist/v/pattern-lab/styleguidekit-assets-default.svg)](https://packagist.org/packages/pattern-lab/styleguidekit-assets-default) [![Gitter](https://img.shields.io/gitter/room/pattern-lab/frontend-viewer.svg)](https://gitter.im/pattern-lab/frontend-viewer)

# Custom StyleguideKit for myLT

These static assets control the look, feel, and functionality of the front-end of Pattern Lab Node for myLT.

## Installation

* Clone the repository into `node_modules`

## Development Requirements

In order to modify these assets you need to install the following:

* [Pattern Lab Node Core](https://github.com/pattern-lab/patternlab-node)
* [Pattern Lab Node Edition](https://github.com/pattern-lab?utf8=%E2%9C%93&query=edition-node)
* [Node.js](http://nodejs.org) and NPM
* [Bower](http://bower.io)
* [Ruby Sass](http://sass-lang.com/install)

## Development Set-up

Once you've installed the requirements do the following to set-up for development:

1. `cd /path/to/node-edition/node_modules/styleguidekit-assets-mylt`
2. `npm install`
3. `bower install`
4. In `patternlab-config.json` replace `"styleguide" : "./node_modules/styleguidekit-assets-default/dist/"` with `"styleguide" : "./node_modules/styleguidekit-assets-mylt/dist/"`

## Making Changes

To make changes **always edit files in `src/`**. To make sure that these changes are reflected in the front-end and `dist/` folder run the following:

    gulp

At this point changes to the static assets should compile to the correct locations in the project as well as `dist/`.
