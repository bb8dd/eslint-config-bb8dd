<<<<<<< HEAD
?
## env
?
React + Typescript
?
## Usage
?
=======
# eslint-config-bb8dd

## env

React + Typescript

## Usage

>>>>>>> 7899e8351c12f19811fb521ffa9f3568c8741125
```yarn
yarn add eslint-config-bb8dd
```
```node
npm install eslint-config-bb8dd
```
<<<<<<< HEAD

code
```js
// .eslintrc.js
module.exports = {
  env: {
    browser: true,
    es2021: true
  },
  parser: '@typescript-eslint/parser',
  extends: [
    'plugin:@typescript-eslint/recommended',
    'plugin:react/recommended',
    'airbnb',
    'airbnb-typescript'
  ],
  overrides: [
  ],
  parserOptions: {
    project: ['./**/tsconfig.json', './tsconfig.json'],
    ecmaVersion: 'latest',
    sourceType: 'module'
  },
  plugins: [
    '@typescript-eslint',
    'react'
  ],
  rules: {
    'import/extensions': [
      'error',
      'ignorePackages',
      {
        js: 'never',
        jsx: 'never',
        ts: 'never',
        tsx: 'never',
      },
    ],
    'react/jsx-filename-extension': [2, { extensions: ['.js', '.jsx', '.ts', '.tsx'] }],
    'linebreak-style': 0,
    'jsx-a11y/label-has-associated-control': 0,
    '@typescript-eslint/member-delimiter-style': 'error', 
    '@typescript-eslint/semi': 'error'
  },
  settings: {
    'import/resolver': {
      node: {
        extensions: ['.js', '.jsx', '.ts', '.tsx'],
      },
    },
  },
  ignorePatterns: ['.eslintrc.js']
}

```
=======
>>>>>>> 7899e8351c12f19811fb521ffa9f3568c8741125
