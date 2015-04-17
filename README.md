# List Bare

The Predix Experience List Bare module simply removes bullets and indents from lists. This module is a fork of the [inuitcss list-bare module](https://github.com/inuitcss/objects.list-bare).

## Dependencies

Px's List Bare module depends on two other Px and inuitcss modules:

* [px-defaults-design](https://github.sw.ge.com/PXd/px-defaults-design)
* [px-functions-design](https://github.sw.ge.com/PXd/px-functions-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.sw.ge.com/PXd/px-list-bare-design.git

Once installed, `@import` into your project's Sass file in its Objects layer:

    @import "../px-list-bare-design/objects.list-bare";

See [px-getting-started](https://github.sw.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Import once

All rulesets are wrapped in the following `@if` statement:

    @if import-once('objects.list-bare') { ... }

## Usage

Basic usage of the List Bare module uses one required class:

    <ul class="list-bare">
        <li>Foo</li>
        <li>Bar</li>
        <li>Baz</li>
    </ul>

The only valid children of the `.list-bare` node are `<li>`s.
