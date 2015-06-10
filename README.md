# Viewport

Default viewport parameters for Predix Experience.

## Sass Documentation

You can review Sass Documentation here: https://github.build.ge.com/pages/PXd/px-viewport-design/sassdoc

## Dependencies

Px's Viewport module depends on one other Px and one other inuitcss modules:

* [tools.responsive](https://github.com/inuitcss/tools.responsive)
* [px-functions-design](https://github.build.ge.com/PXd/px-functions-design)

## Upstream dependency

The Viewport module is also an upstream dependency in this meta kit:

* [px-starter-kit-design](https://github.build.ge.com/PXd/px-starter-kit-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.build.ge.com/PXd/px-viewport-design.git

Once installed, `@import` into your project's Sass file in its Base layer:

    @import "../px-viewport-design/base.viewport";

See [px-getting-started](https://github.build.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Import once

All rulesets are wrapped in the following `@if` statement:

    @if import-once('base.viewport') { ... }

## Usage

The following variables are available for use in the module:

    $desk-wide-width

This should be the widest (in `rem`'s you wish the overall "page" to be, and will be added as the widest breakpoint for responsive mixin).
