# BBB Generator [![Build Status](https://secure.travis-ci.org/SBoudrias/generator.png?branch=master)](https://travis-ci.org/SBoudrias/generator)

The Backbone-Boilerplate generator working on top of Yeoman.

**Project stage**: This is early alpha functionnalities. The generator is not yet published on NPM, it's only usable if installed manually.

## Installation
- Make sure you have [yo](https://github.com/yeoman/yo) installed:
    `npm install -g yo`
- Install the generator: `npm install generator-bbb` (This generator is not yet on NPM)

### From Scratch

Run `yo bbb` to start the default scaffholding

### Include in existing project

Run `yo bbb:init` to initialize the generator configuration. This will allow you to use the generator on an existing project.

### Create module

Run `yo bbb:module` to create a module.

## Developpement

### Installation

In order to work with the developpement version, you'll need to use [`npm-link` functionnality](https://npmjs.org/doc/link.html).

```cmd
$ cd install/dir
$ git clone repo/generator-bbb.git .
$ npm install # Get the dependencies manually
$ npm link # Here you create a global link to `generator-bbb` which will be use by NPM
$ cd dir/to/use/as/target
$ npm install generator-bbb # Yeoman search local generator
$ yo bbb # or any BBB generator options
```

## License
[MIT License](http://en.wikipedia.org/wiki/MIT_License)