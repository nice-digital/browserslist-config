# NICE Digital Browserslist

> Shared Browserslist config for use in NICE Digital Services

[![npm](https://img.shields.io/npm/v/@nice-digital/browserslist-config.svg)](https://www.npmjs.com/package/@nice-digital/browserslist-config)
[![GitHub release](https://img.shields.io/github/release/nice-digital/browserslist-config.svg)](https://github.com/nice-digital/browserslist-config)
[![License](https://img.shields.io/github/license/nice-digital/browserslist-config.svg)](https://github.com/nice-digital/browserslist-config/blob/master/LICENSE)
[![Dependencies](https://img.shields.io/david/nice-digital/browserslist-config.svg)](https://david-dm.org/nice-digital/browserslist-config)

## Installation

With npm:

```sh
npm install @nice-digital/browserslist-config --save-dev
```

Or with Yarn:

```sh
yarn add @nice-digital/browserslist-config -D
```

## Usage

Add this to your *package.json* file:

```json
"browserslist": [
    "extends @nice-digital/browserslist-config"
]
```

Or use a _.browserslistrc_ [as per the docs](https://github.com/browserslist/browserslist#config-file).

## V2 Breaking changes

Version 2 drops support for IE versions below 11. Use v1 for support for older browsers.