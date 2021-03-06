# generator-nm-standard
[![Build Status](https://travis-ci.org/millette/generator-nm-standard.svg?branch=master)](https://travis-ci.org/millette/generator-nm-standard)
[![Coverage Status](https://coveralls.io/repos/github/millette/generator-nm-standard/badge.svg?branch=master)](https://coveralls.io/github/millette/generator-nm-standard?branch=master)
[![Dependency Status](https://gemnasium.com/badges/github.com/millette/generator-nm-standard.svg)](https://gemnasium.com/github.com/millette/generator-nm-standard)

> Scaffold out a [node module](https://github.com/sindresorhus/node-module-boilerplate), with standard code style

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

Based on generator-nm by [Sindre Sorhus](https://www.npmjs.com/~sindresorhus) but where xo is replaced by the [standard](https://github.com/feross/standard) linter.

![](screenshot.png)


## Install

```
$ npm install --global generator-nm-standard
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo nm-standard
```

## Warning
Do not use version 3.1.11, it was mistagged and won't work with ```yo``` 1.7.x or earlier.
```generator-nm-standard``` 3.1.10 and earlier will work with older ```yo```.

Use 3.2.0 instead if you want to update ```yo``` to 1.8.x.


## Tip

Use [chalk](https://github.com/sindresorhus/chalk) if you want colors in your CLI.


## License
Based on MIT © [Sindre Sorhus' word](http://sindresorhus.com).

MIT © [Robin Millette](http://robin.millette.info)
