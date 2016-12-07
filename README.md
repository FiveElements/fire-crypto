# \<fire-crypto\> [![Build Status](https://travis-ci.org/FiveElements/fire-crypto.svg?branch=master)](https://travis-ci.org/FiveElements/fire-crypto) 
[![Code Climate](https://codeclimate.com/github/FiveElements/fire-crypto/badges/gpa.svg)](https://codeclimate.com/github/FiveElements/fire-crypto)
[![Test Coverage](https://codeclimate.com/github/FiveElements/fire-crypto/badges/coverage.svg)](https://codeclimate.com/github/FiveElements/fire-crypto/coverage)
[![Issue Count](https://codeclimate.com/github/FiveElements/fire-crypto/badges/issue_count.svg)](https://codeclimate.com/github/FiveElements/fire-crypto)

Polymer crypto 

# Documentation

## Webcrypto
Chrome : https://sites.google.com/a/chromium.org/dev/blink/webcrypto
MDN: https://developer.mozilla.org/en-US/docs/Web/API/SubtleCrypto/sign
Sample: https://github.com/diafygi/webcrypto-examples

TODO encrypt https://blog.engelke.com/2014/08/23/public-key-cryptography-in-the-browser/

Encoding: https://coolaj86.github.io/web-crypto-utahjs-preso/

## Install the Polymer-CLI

First, make sure you have the [NodeJs](https://nodejs.org/en/) installed. Then run `npm run dev-install` to install all global dependencies to run your application locally.

## Viewing Your Web Components Demo

```
$ npm run dev
```

## Test Your Web Components

```
$ npm run test
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
$ npm run test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

 