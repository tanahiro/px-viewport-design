# Viewport

Default viewport definition for Predix Experience.

## Dependencies

Px's Viewport module depends on two other Px and inuitcss modules:

* [tools.responsive](https://github.com/inuitcss/tools.responsive)
* [px-functions-design](https://github.sw.ge.com/PXd/px-functions-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.sw.ge.com/PXd/px-viewport-design.git

Once installed, `@import` into your project's Sass file in its Base layer:

    @import "../px-viewport-design/base.viewport";

See [px-getting-started](https://github.sw.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Import once

All rulesets are wrapped in the following `@if` statement:

    @if import-once('base.viewport') { ... }

## Usage

The following variables are available for use in the module:

    $desk-wide-width

This should be the widest (in `em`'s you wish the overall "page" to be, and will be added as the widest breakpoint for responsive mixin.
