![license](https://img.shields.io/github/license/pattern-lab/styleguidekit-assets-default.svg)

# Custom StyleguideKit for myLT

These static assets control the look, feel, and functionality of the front-end of Pattern Lab Node for myLT.

## Installation

* Clone the repository into `node_modules`

## Development Requirements

In order to modify these assets you need to install the following:

* [Pattern Lab Node Core](https://github.com/pattern-lab/patternlab-node)
* [Pattern Lab Node - Gulp Edition](https://github.com/pattern-lab/edition-node-gulp)
* [Node.js](http://nodejs.org) and NPM
* [Bower](http://bower.io)
* [Ruby Sass](http://sass-lang.com/install)

## Development Set-up

Once you've installed the requirements do the following to set-up for development:

1. `cd /path/to/node-edition/node_modules/styleguidekit-assets-mylt`
2. `npm install`
3. `bower install`
4. In `patternlab-config.json` replace `"styleguide" : "./node_modules/styleguidekit-assets-default/dist/"` with `"styleguide" : "./node_modules/styleguidekit-assets-mylt/dist/"` to reference your StyleguideKit

## Making Changes

To make changes **always edit files in `src/`**. To make sure that these changes are reflected in the front-end and `dist/` folder run the following:

    gulp

At this point changes to the static assets should compile to the correct locations in the project as well as `dist/`.
