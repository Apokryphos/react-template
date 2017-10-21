# React Template

Boilerplate setup for React projects.

- Babel
- ESLint
- Flow
- Jest
- React
- SCSS
- Webpack

## npm Scripts
---

Production build:
```shell
npm run build
```

Development build using Webpack DevServer:
```shell
npm start
```

Run tests (ESLint, Flow, Jest):
```shell
npm test
```

## Webpack Configs
---

Webpack configurations are separated into three files:

- webpack.common.config.js
- webpack.development.config.js
- webpack.production.config.js

## Dependencies
---

### React
- classnames
- prop-types
- react
- react-dom

## Development Dependencies

### Babel
- babel-core
- babel-eslint
- babel-jest
- babel-loader
- [babel-plugin-module-resolver](https://github.com/tleunen/babel-plugin-module-resolver)
- babel-preset-env
- babel-preset-flow
- babel-preset-react

### ESLint
- eslint
- eslint-config-airbnb
- [eslint-import-resolver-babel-module](https://github.com/tleunen/eslint-import-resolver-babel-module)
- eslint-plugin-compat
- eslint-plugin-flowtype
- [eslint-plugin-import](https://github.com/benmosher/eslint-plugin-import)
- eslint-plugin-jsx-a11y
- eslint-plugin-react

### Flow
- flow-bin

### Git Hooks
- [husky](https://github.com/typicode/husky)

### SCSS
- css-loader
- sass-loader
- style-loader
- node-sass

### Tests
- jest
- react-test-renderer

### Webpack
- webpack
- webpack-dev-server
- webpack-merge
- clean-webpack-plugin
- compression-webpack-plugin
- copy-webpack-plugin
- extract-text-webpack-plugin
