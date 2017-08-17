# jest-addons

[![npm](https://img.shields.io/npm/v/jest-addons.svg)](https://www.npmjs.com/package/jest-addons)
[![npm](https://img.shields.io/npm/dt/jest-addons.svg)](https://www.npmjs.com/package/jest-addons)
[![npm](https://img.shields.io/npm/l/jest-addons.svg)](https://github.com/negativetwelve/jest-addons/blob/master/LICENSE)
[![CircleCI branch](https://img.shields.io/circleci/project/github/negativetwelve/jest-addons/master.svg)](https://circleci.com/gh/negativetwelve/jest-addons)

Super-package of jest addons. Currently includes:

* [jest-context](https://github.com/negativetwelve/jest-context)
* [jest-its](https://github.com/negativetwelve/jest-its)
* [jest-set](https://github.com/negativetwelve/jest-set)

## Getting Started

Install `jest-addons` using `yarn`:

```shell
yarn add --dev jest-addons
```

## Usage

Add an entry to your jest configuration `setupFiles` in your `package.json`:

```json
"jest": {
  "setupFiles": [
    "jest-addons/setup"
  ]
}
```
