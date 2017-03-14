# eslint-config-meridian

## How to Use

```shell
npm i -D prettier
npm i -D @joefraley/eslint-config
```

```json
# package.json
{
  ...
  "scripts": {
    "lint": "eslint --fix"
  }
}
```

```javascript
// .eslintrc.js
module.exports = {
  extends: '@joefraley',
  parser: 'babel-eslint',
};
```

## Editor Integration

[Install prettier for atom](https://atom.io/packages/prettier-atom): auto lint fixing on save.

## Configuration Settings

[`eslint:recommended`](http://eslint.org/docs/rules/) (everything w/ a checkmark)
[`plugin:react/recommended`](https://github.com/yannickcr/eslint-plugin-react#recommended)
[`prettier`](https://github.com/prettier/eslint-config-prettier#installation) (turn off style related rules above like quote type)
[`prettier/react`](https://github.com/prettier/eslint-config-prettier/blob/d0a7f0773780d87564359ef46c0b6e4e3a71a426/react.js)
