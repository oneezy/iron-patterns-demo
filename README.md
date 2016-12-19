_[Demo and API Docs](https://oneezy.github.io/iron-patterns-demo)_

# Iron Patterns Demo

[![Build Status](https://travis-ci.org/iron-patterns-demo.svg?branch=master)](https://travis-ci.org/iron-patterns-demo)
[![GitHub release](https://img.shields.io/github/release/iron-patterns-demo.svg)](https://github.com/iron-patterns-demo/releases)
[![license](https://img.shields.io/github/license/iron-patterns-demo.svg)](https://github.com/iron-patterns-demo/blob/master/LICENSE)
[![](https://img.shields.io/github/issues-raw/iron-patterns-demo.svg)](https://github.com/iron-patterns-demo/issues)


## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.