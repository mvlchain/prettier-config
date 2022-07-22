# @mvlchain/prettier-config

Common Prettier config used in MVL FE projects.

- [Install](#install)
- [Usage](#usage)
  - [.prettierrc.js](#prettierrcjs)
    - [Overwrite](#overwrite)
  - [package.json](#packagejson)

## Install

```bash
yarn add -D @mvlchain/prettier-config
```

## Usage

### .prettierrc.js

1. Add the following to `.prettierrc.js` (or `prettier.config.js`):

```js
module.exports = require('@mvlchain/prettier-config');
```

#### Overwrite

You can overwrite config.

```js
module.exports = {
  ...require('@mvlchain/prettier-config'),
  // overwrite
  printWidth: 140,
  tabWidth: 4,
};
```

### package.json

1. Add the following to `package.json`:

```json
"prettier": "@mvlchain/prettier-config",
```
