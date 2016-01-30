# eslint-config-commandp

## Usage
Export three ESLint configurations for usage.

### ES6
Including ES6 eslint rules, base on [eslint-config-standard]. Requires `eslint` and `babel-eslint`.

1. `npm install --save-dev eslint-config-commandp babel-eslint eslint`
2. add `"extends": "commandp"` to your `.eslintrc`

```json
{
  "extends": "commandp"
}
```

### React
Lint ES6+ and React, base on [eslint-config-airbnb]. Requires `eslint`, `babel-eslint` and  `eslint-plugin-react`.

1. `npm install --save-dev eslint-config-commandp eslint babel-eslint eslint-plugin-react`
2. add `"extends": "commandp/react"` to `.eslintrc`

```json
{
  "extends": "commandp/react"
}
```

### React Native
Lint ES6+, React and add some available global values for React Native.

1. `npm install --save-dev eslint-config-commandp eslint babel-eslint eslint-plugin-react`
2. add `"extends": "commandp/react-native"` to `.eslintrc`

```json
{
  "extends": "commandp/react-native"
}
```

[eslint-config-standard]: https://github.com/feross/eslint-config-standard
[eslint-config-airbnb]: https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb
