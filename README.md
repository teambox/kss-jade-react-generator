# kss-jade-react-generator
A [kss-node](http://kss-node.github.io/kss-node/)'s generator - supporting [Jade](http://jade-lang.com/) and [React](https://facebook.github.io/react/) component

## Overview
This is mostly a direct translation of the kss-node's default Handlebars generator, but few changes are added.

In addition to Jade, React components can be used as the external markup file.

### Features
- Plain HTML and Jade as inline markup
- Plain HTML, Jade and React component as external files
- Load the custom helpers which can be used within a template

## Usage and Examples
See the [example](https://github.com/kotorieclair/kss-jade-react-generator/tree/master/example) folder for usage details.

The example style guide using the folder above can be generated through a [Gulp](http://gulpjs.com/) task.
```bash
$ gulp kss
```
Then, open the generated style guide with
```bash
$ gulp kss:open
```

**WIP**
