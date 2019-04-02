# Contao Choices Bundle Assets

This package contains the frontend assets of the composer bundle heimrichhannot/contao-choices-bundle.

## Install

Typicall this package comes with [Contao Choices Bundle](https://github.com/heimrichhannot/contao-choices-bundle). If you want to install it by yourself: 

```npm
yarn add @hundh/contao-choices-bundle
```

## Usage

If you want to use the bundle independent of Choices Bundle: 

```js
import ChoicesBundle from '@hundh/contao-choices-bundle'

ChoicesBundle.init();
```

Afterwards choices.js is appended to all inputs/select with attribute `data-choices=1`. You can pass additional options as json string in `data-choices-options` attribute.