# eslint-config-@joefraley

A custom eslint configuration for my JavaScript projects. It defers to the official recommended settings for code quality concerns. It defers to prettier for aesthetic style concerns.

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

## MIT License

Copyright (c) 2015 Gleb Bahmutov

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.