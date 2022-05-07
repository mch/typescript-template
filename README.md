# TypeScript Template Project

This is a minimal template project for TypeScript development, e.g. for use in a [Code Retreat](https://www.coderetreat.org/), especially for use with [mob.sh](https://mob.sh/).

This branch adds support for using ES Modules. For more information on ESM, see:
- Writing a [Pure ESM package](https://gist.github.com/sindresorhus/a39789f98801d908bbc7ff3ecc99d99c)
- [JavaScript Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)
- [Announcing TypeScript 4.7 Beta, ECMAScript Module Support in Node.js](https://devblogs.microsoft.com/typescript/announcing-typescript-4-7-beta/#ecmascript-module-support-in-node-js)
- [Mocha: Node.js Native ESM Support](https://mochajs.org/#nodejs-native-esm-support)
  - [Mocha: support ESM in watch mode](https://github.com/mochajs/mocha/issues/4374)

This was added because some packages now provide only ES modules, and not commonjs ones.

## Quick Start

1. Create a repository from this template. See [Creating a repository from a template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-repository-from-a-template) for more information.
2. Install the dependencies: `npm install`
3. Edit `test/test.ts`.
4. Run the tests with `npm run test`.

## Default Tools
- [Mocha](https://mochajs.org/) is used as the test running.
- [Chai](https://www.chaijs.com/) is used for assertions.
- [Prettier](https://prettier.io/) is available to standardize code style.
