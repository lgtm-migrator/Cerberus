# Cerberus

[![Build Status](https://travis-ci.com/Jithinqw/Cerberus.svg?token=WuVynuX3ULHwMq3Ky4qo&branch=dev)](https://travis-ci.com/Jithinqw/Cerberus)

Validations made easy

## Vision

Unlike other validation packages the vision of this package is to reduce the number of lines written for validations and other information to be retrieved from data.

## Requirements

Cerebrus runs on bare `NodeJS(v6.0)` or later. Cerebrus tests configured to run on `Nodejs v6.0 - v12.0`.
Check `travis CI` build for test runs.

## Installation

Install this package using `npm i cerberus-validator`.

## Testing

Cereberus uses `assert` library from `NodeJS` and use `mocha` for test runners.

For running tests install `mocha` by using `npm i mocha -g` and run `mocha` from root of the project.

## TODO

- [ ] Move all the validations from Nodejs to browser.
- [ ] Generate `.min` file.
- [ ] Move to `Promise` based library.

## Using it on your browser

You can use `cerberus` in your browser by simply importing it.

```javascript
    <script src="build/index.js"></script>
```

## Examples

View examples in `example.md`