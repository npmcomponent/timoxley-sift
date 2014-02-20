*This repository is a mirror of the [component](http://component.io) module [timoxley/sift](http://github.com/timoxley/sift). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/timoxley-sift`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# sift

Fast String Distance (SIFT) Algorithm.

[![NPM](https://nodei.co/npm/sift-string.png)](https://nodei.co/npm/sift-string/)

[![Build Status](https://travis-ci.org/timoxley/sift.png?branch=master)](https://travis-ci.org/timoxley/sift)

[![Dependency Status](https://david-dm.org/timoxley/sift.png)](https://david-dm.org/timoxley/sift)

## Installation

#### Browserify/Node

    $ npm install sift-string


#### Component

    $ component install timoxley/sift

## Demo

[Demo](http://timoxley.github.com/sift/examples/spellcheck/)

or if you want to check it out locally:

```bash
# run only once to install npm dev dependencies
npm install .
# this will install && build the components and open the demo web page
npm run c-demo
```

## API

### sift(string, string)

Return 'distance' between two strings.

## TODO

* Dictionary Helper supply it emits suggestions.

## Credit

Code extracted from [MailCheck](https://github.com/kicksend/mailcheck)

Big thanks to [Alexandru Vladutu](https://github.com/alessioalex) for his contributions!

## License

  MIT
