<p align="center"><img src="./assets/example.png" /></p>

<h1 align="center">Gradient Avatar</h1>

<p align="center">🌈 Beautiful default avatars.</p>
<p align="center">
  <a href="https://travis-ci.org/varld/gradient-avatar">
    <img src="https://travis-ci.org/varld/gradient-avatar.svg?branch=master" alt="Build Status" />
  </a>
  <a href="https://codecov.io/gh/varld/gradient-avatar">
    <img src="https://codecov.io/gh/varld/gradient-avatar/branch/master/graph/badge.svg" />
  </a>
</p>

## About 

Generate beautiful and unique avatars for your users. `gradient-avatar` was inspired by Zeit.

`gradient-avatar` is also available as a [microservice](https://github.com/usemeta/gradient-avatar-service).

## Install

```
$ npm install gradient-avatar
```

## Usage

```js
const avatar = require('gradient-avatar');

avatar('uid');
// => the avatar svg
```

## API

### avatar(seed[, size])

#### seed

Type: `string`

The seed for the generated avatar. 

#### size

Type: `number`

The generated svg's size.

#### Returns

Type: `string`

The generated avatar svg.

## License

MIT © [Tobias Herber](https://github.com/herber)

[![Made by Varld](https://potato.varld.co/oss/badge.svg)](https://varld.co)
