# eslint-config-saltire-node

*A JS ESLint config for @saltire's personal projects.*

A fork of the Airbnb style guide at: https://github.com/airbnb/javascript

### Install

1. Install the package and its peer dependencies:
   ```
   npm install --save-dev eslint eslint-plugin-import eslint-config-airbnb-base q4mobile/eslint-config-saltire-node
   ```

2. Add `"extends": "saltire-node"` to your .eslintrc file.

### Run

If you installed the packages locally, run the local eslint binary:
`./node_modules/.bin/eslint .`

If you installed *all* the packages globally with `npm install -g`, you can run the global eslint: `eslint .`
