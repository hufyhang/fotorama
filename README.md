# Changes to original Fotorama

* Added `alt` attribute support. Lazy-loading is also support. i.e. `<a href="photo.png" alt="This is an image">`

* Added tablet mode to specify Fotorama instances' height on tablets.

Usage:


```jade
.fotorama.fotorama-container(data-tablet-to="1200px", data-tablet-height="100px", data-minheight="100px", data-width="100%")
```


# Fotorama source

There is nothing for non-coders. Take the latest and ready-to-use Fotorama on its website:<br>
> **http://fotorama.io/set-up**

## How to build
First, ensure that you have the latest [Node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed.

Test that Grunt’s CLI is installed by running `grunt --version`.  If the command isn’t found, run `npm install -g grunt-cli`.  For more information about installing Grunt, see the [getting started guide](http://gruntjs.com/getting-started).

1. Fork and clone the repo.
2. Run `npm install` to install all dependencies (including Grunt).
3. Run `grunt` to grunt this project.

Hack on by running `grunt watch` and editing files in the `src/` subdirectory.

The built version of Fotorama will be put in the `out/`.

## Submitting pull requests
1. Create a new branch, please don’t work in your `master` branch directly.
2. Add stuff.
3. Push to your fork and submit a pull request to Fotorama’s `develop` branch.

Regarding code style like indentation and whitespace, follow the conventions you see used in the source already.
