![alt tag](https://raw.github.com/dogfalo/materialize/master/images/materialize.gif)
===========

[![Travis CI](https://travis-ci.org/Dogfalo/materialize.svg?branch=master)](https://travis-ci.org/Dogfalo/materialize)[![devDependency Status](https://david-dm.org/Dogfalo/materialize/dev-status.svg)](https://david-dm.org/Dogfalo/materialize#info=devDependencies)[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/Dogfalo/materialize?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[Materialize](http://materializecss.com/), a CSS Framework based on material design

## Note for AMD-compatible version

**Notice that this is NOT the offical AMD-compatible version, and I won't keep updating it with latest commit (just stable release), so just use `dist/js/materialize.js`.**

This modified version is tested and passed on [curl.js](https://github.com/cujojs/curl), I'm not sure that it would compatible with other AMD module.

After required it at the first time, please do `Waves.displayEffect()` to show waves, like this:

```
require(['jquery']).next(['materialize'], function(Materialize){
    // add it when you required Materialize at the first time
    Waves.displayEffect();

    // do more things with Materialize here
});
```

For modified parts, see original issue here: https://github.com/Dogfalo/materialize/issues/634#issuecomment-183846293


### Current Version : v0.97.8

## Sass Requirements:
- Ruby Sass 3.3+, LibSass 0.6+

## Supported Browsers:
Chrome 35+, Firefox 31+, Safari 7+, IE 10+

## Changelog
- v0.97.8 (October 30th)
  - **Refactored Modal plugin**
  - Tabs now supported in navbar
  - Chips data can now be reinitiailized
  - Minor side nav fixes
  - FAB to toolbar component added
  - Fixed dropdown options bug
- v0.97.7 (July 23rd)
  - Basic horizontal cards
  - Carousel bug fixes and new features
  - Updated sidenav styles and new component
  - Meteor package now supports Sass
  - Autocomplete form component
  - Chips jQuery plugin
- v0.97.6 (April 1st)
  - **Removed deprecated material icons from project**
  - **Changed /font directory to /fonts**
  - Datepicker and ScrollSpy now compatible with jQuery 2.2.x
  - Responsive tables now work with empty cells
  - Added focus states to checkboxes, switches, and radio buttons
  - Sidenav and Modals no longer cause flicker with scrollbar
  - Materialbox overflow and z-index issues fixed
  - Added new option for Card actions within a Card reveal
- v0.97.5 (Dec 21, 2015)
  - Fixed Meteor package crash



## Contributing
[Please read CONTRIBUTING.md for more information](CONTRIBUTING.md)

## Testing
We use Jasmine as our testing framework and we're trying to write a robust test suite for our components. If you want to help, [here's a starting guide on how to write tests in Jasmine](https://docs.google.com/document/d/1dVM6qGt_b_y9RRhr9X7oZfFydaJIEqB9CT7yekv-4XE/edit?usp=sharing)
