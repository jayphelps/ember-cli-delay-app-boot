# ember-cli-delay-app-boot

This addon adds a 250ms delay to initial application boot.  This seems pretty silly to most folks, and is only something you
should include if you are struggling with Chrome loading your sourcemap files. Adding a small amount of async during app boot
allows Chrome to grab the sourcemaps before kicking off the app load process (and hitting any debuggers you might have).

## Installation

* `git clone` this repository
* `npm install`
* `bower install`

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
