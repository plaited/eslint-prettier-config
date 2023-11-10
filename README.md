# Plaited eslint prettier config presets

[![Test](https://github.com/plaited/eslint-prettier-config/actions/workflows/tests.yml/badge.svg)](https://github.com/plaited/eslint-prettier-config/actions/workflows/tests.yml)

An opinionated Eslint config used for Plaited repositories.

## Installation

Install eslint and this config:

```
npm i -D eslint @plaited/eslint-prettier-config
```

Now in your `.eslintrc.cjs`:

```js
module.exports = {
  extends: ['@plaited/eslint-prettier-config'],
  // ... any other configuration overrides ...
}
```

Now in you `prettier.config.cjs`

```js
module.exports = {
  ...require('@plaited/eslint-prettier-config/prettier'),
  ... // Override properties if needed
}
```
