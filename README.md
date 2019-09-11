# @nuxt/blueprints

> Module for Nuxt.js to create distributable micro-apps

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Circle CI][circle-ci-src]][circle-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

## :construction: WIP

This module is considered experimental and a work-in-progress.

## Examples

Check the [example](./example) for a simple blueprint example.

If you are looking for a more advanced example, have a look at the [NuxtPress repository](https://github.com/nuxt/press) which is also build using blueprints.

## Edge dependency

At this moment the blueprints module only works with [`nuxt-edge`](https://www.npmjs.com/package/nuxt-edge) as some required Nuxt.js features have not yet been released officially.

If you wish to run the example from this repo, you need to use at least [Node v12.4.0](https://node.green/#ESNEXT-candidate--stage-3--static-class-fields) due to the use of [static class features](https://github.com/tc39/proposal-static-class-features/). Those are transpiled on release using [@babel/plugin-proposal-class-properties](https://babeljs.io/docs/en/babel-plugin-proposal-class-properties), but the example runs from source.

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Nuxt.js Team

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/@nuxt/blueprints/latest.svg?style=flat-square
[npm-version-href]: https://npmjs.com/package/@nuxt/blueprints

[npm-downloads-src]: https://img.shields.io/npm/dt/@nuxt/blueprints.svg?style=flat-square
[npm-downloads-href]: https://npmjs.com/package/@nuxt/blueprints

[circle-ci-src]: https://img.shields.io/circleci/project/github/nuxt/blueprints.svg?style=flat-square
[circle-ci-href]: https://circleci.com/gh/nuxt/blueprints

[codecov-src]: https://img.shields.io/codecov/c/github/nuxt/blueprints.svg?style=flat-square
[codecov-href]: https://codecov.io/gh/nuxt/blueprints

[license-src]: https://img.shields.io/npm/l/@nuxt/blueprints.svg?style=flat-square
[license-href]: https://npmjs.com/package/@nuxt/blueprints
