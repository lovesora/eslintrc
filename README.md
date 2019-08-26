# Deprecated
see [lintrc](https://github.com/lovesora/lintrc)

# eslintrc
eslint configuration

# Usage
## Step 1. Install eslintrc
```bash
yarn add --dev eslint babel-eslint eslintrc
```

## Step 2. Add `.eslintrc` in your project root
```js
{
  "extends": "./node_modules/eslintrc/.eslintrc-default"
}
```

or
```bash
cp ./node_modules/eslintrc/.eslintrc .eslintrc
```

