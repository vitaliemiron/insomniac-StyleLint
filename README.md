# Recess\* Property Order [<img src="https://s3.amazonaws.com/media-p.slid.es/uploads/467124/images/2872758/stylelint-icon-black.svg" alt="StyleLint" width="90" height="90" align="right">][stylelint]

[![npm version][npm-img]][npm-url]
[![npm downloads][npm-dls]][npm-url]
[![dependency status][david-img]][david-url]
[![build status][travis-img]][travis-url]
[![github issues][issues-img]][issues-url]

# insomniac-stylelint

Insomniac StyleLint extensible and sharable configuration.

Config sorts CSS properties the way [Recess][] did and
Bootstrap [did][]/[does][].

## Usage

Install the configuration as a npm package:

```sh
$ npm install --save-dev insomniac-stylelint

# --- OR ---

$ yarn add --dev insomniac-stylelint
```

and then add it as extension in your `.stylelintrc.json` file:

```json
{
  "extends": ["insomniac-stylelint"]
}
```

The corresponding `.stylelintrc.yaml` file looks like this:

```json
extends:
  - insomniac-stylelint
```

## Visual Studio Code

```
  Install extension stylelint
  Reload VS Code
```

## References
[@mdo on CSS Property Order][mdo-order]
[npm-url]: https://www.npmjs.com/package/stylelint-config-recess-order
[npm-img]: https://img.shields.io/npm/v/stylelint-config-recess-order.svg?style=flat-square
[npm-dls]: https://img.shields.io/npm/dt/stylelint-config-recess-order.svg?style=flat-square
[david-url]: https://david-dm.org/stormwarning/stylelint-config-recess-order
[david-img]: https://img.shields.io/david/stormwarning/stylelint-config-recess-order.svg?style=flat-square
[travis-url]: https://travis-ci.org/stormwarning/stylelint-config-recess-order
[travis-img]: https://img.shields.io/travis/stormwarning/stylelint-config-recess-order.svg?style=flat-square
[issues-url]: https://github.com/stormwarning/stylelint-config-recess-order/issues
[issues-img]: https://img.shields.io/github/issues/stormwarning/stylelint-config-recess-order.svg?style=flat-square
[stylelint]: https://github.com/stylelint/stylelint
[recess]: https://github.com/twitter/recess/blob/29bccc870b7b4ccaa0a138e504caf608a6606b59/lib/lint/strict-property-order.js
[did]: https://github.com/twbs/bootstrap/blob/f58997a0dae54dc98d11892afef9acb85bdc6a1e/.scss-lint.yml#L136
[does]: https://github.com/twbs/bootstrap/blob/ba878eb542ab6c04786741569ba089d02e9bea46/.stylelintrc#L36
[mdo-order]: http://markdotto.com/2011/11/29/css-property-order/