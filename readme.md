# is-google-domain

**Tells you if a top level domain is a Google domain.**

[![npm status](http://img.shields.io/npm/v/is-google-domain.svg?style=flat-square)](https://www.npmjs.org/package/is-google-domain) [![Travis build status](https://img.shields.io/travis/vweevers/is-google-domain.svg?style=flat-square&label=travis)](http://travis-ci.org/vweevers/is-google-domain) [![AppVeyor build status](https://img.shields.io/appveyor/ci/vweevers/is-google-domain.svg?style=flat-square&label=appveyor)](https://ci.appveyor.com/project/vweevers/is-google-domain) [![Dependency status](https://img.shields.io/david/vweevers/is-google-domain.svg?style=flat-square)](https://david-dm.org/vweevers/is-google-domain)

## `isGoogle(domain, subdomains = true)`

```js
const isGoogle = require('is-google-domain')

isGoogle('google.co.jp') === true;
isGoogle('mail.google.com') === true;
isGoogle('mail.google.com', false) === false;
```

## install

With [npm](https://npmjs.org) do:

```
npm install is-google-domain
```

## license

[MIT](http://opensource.org/licenses/MIT) © Vincent Weevers
