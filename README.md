# nuxt-google-tag-manager
[![npm (scoped with tag)](https://img.shields.io/npm/v/nuxt-google-tag-manager/latest.svg?style=flat-square)](https://npmjs.com/package/nuxt-google-tag-manager)
[![npm](https://img.shields.io/npm/dt/nuxt-google-tag-manager.svg?style=flat-square)](https://npmjs.com/package/nuxt-google-tag-manager)
[![CircleCI](https://img.shields.io/circleci/project/github/DaxChen/nuxt-google-tag-manager.svg?style=flat-square)](https://circleci.com/gh/DaxChen/nuxt-google-tag-manager)
[![Codecov](https://img.shields.io/codecov/c/github/DaxChen/nuxt-google-tag-manager.svg?style=flat-square)](https://codecov.io/gh/DaxChen/nuxt-google-tag-manager)
[![Dependencies](https://david-dm.org/DaxChen/nuxt-google-tag-manager/status.svg?style=flat-square)](https://david-dm.org/DaxChen/nuxt-google-tag-manager)
[![js-standard-style](https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat-square)](http://standardjs.com)

> Nuxt.js module for google tag manager, forked from official modules repo to add custom settings

[📖 **Release Notes**](./CHANGELOG.md)

## Features

The module features

## Setup
- Add `nuxt-google-tag-manager` dependency using yarn or npm to your project
- Add `nuxt-google-tag-manager` to `modules` section of `nuxt.config.js`

```js
{
  modules: [
    ['@nuxtjs/google-tag-manager', { id: 'GTM-XXXXXXX' }],
  ]
}
```

## Options

### `id`
- Required
Should be in form of `GTM-XXXXXXX`

### Other options
```js
{
  layer: 'dataLayer',
  env: {
    gtm_auth:        '...',
    gtm_preview:     '...',
    gtm_cookies_win: '...'
  },
  scriptURL: '//example.com',
  delay: 300 // (ms) the time delay to wait for page transition before firing event
}
```

## Development

- Clone this repository
- Install dependencies using `yarn install` or `npm install`
- Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) DaxChen <dd@daxchen.com>
