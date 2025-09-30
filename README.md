# bare-bundle-transform-plugin-babel

[![NPM Version](https://img.shields.io/npm/v/bare-bundle-transform-plugin-babel)](https://npmjs.com/package/bare-bundle-transform-plugin-babel)
[![Tests](https://img.shields.io/github/actions/workflow/status/didericis/bare-bundle-transform-plugin-babel/test.yml?label=tests)](https://github.com/Didericis/bare-bundle-transform-plugin-babel/actions/workflows/test.yml)

Plugin for [bare-bundle-transform](https://github.com/Didericis/bare-bundle-transform) that applies a babel transformation to every file with a `.cjs`, `.mjs`, and `.js` extension.

## Usage

```console
bare-pack ./app.js | bare-bundle-transform --plugin bare-bundle-transform-plugin-babel -o ./app.bundle
```

NOTE: to configure babel, add a `babel.config.json` to the root of the project you're bundling (as documented [here](https://babeljs.io/docs/configuration)).
