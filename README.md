# eslint-config-ct-fletcher
[**npm link**](https://www.npmjs.com/package/eslint-config-ct-fletcher)

[**github link**](https://github.com/noahehall/eslint-config-ct-fletcher)

## parser
```
  "parser": "babel-eslint",
```
## extends
```
  "eslint:recommended",
  "defaults/rules/eslint/best-practices/eslint",
  "defaults/rules/eslint/errors/eslint",
  "defaults/rules/eslint/es6/eslint",
  "defaults/rules/eslint/node/eslint",
  "defaults/rules/eslint/strict/eslint",
  "defaults/rules/eslint/style/eslint",
  "defaults/rules/eslint/variables/eslint"
```

## plugins
```
  "react",
  "jsx-a11y",
  "eslint-plugin-flowtype",
  "import"
```

## Include it in your project
**Install it as a dev dependency in your project**
```
$ npm install --save-dev eslint-config-ct-fletcher
```

**update your root/.eslintrc.js**

```
"use strict";

module.exports = {
  "extends": [
    "eslint-config-ct-fletcher"
  ]
}

```
