# Recess\* Property Order

[![npm version][npm-img]][npm-url]
[![npm downloads][npm-dls]][npm-url]
[![dependency status][david-img]][david-url]
[![build status][travis-img]][travis-url]
[![github issues][issues-img]][issues-url]

A [Stylelint][] config that sorts CSS properties the way [Recess][] did and
Bootstrap [did][]/[does][].

\*With some modifications & additions for modern properties.

## Usage

1.  Add [stylelint][] and this package to your project:  
    ```sh
    npm install --save-dev stylelint insomniac-stylelint
    ```
2.  Configure your stylelint configuration file to extend this package:  
    ```js
    {
      "extends": "insomniac-stylelint",
      "rules": {
        // Add overrides and additional rules here
      }
    }
    ```

## References

[@mdo on CSS Property Order][mdo-order]

[npm-url]: https://www.npmjs.com/package/insomniac-stylelint

[npm-img]: https://img.shields.io/npm/v/insomniac-stylelint.svg?style=flat-square

[npm-dls]: https://img.shields.io/npm/dt/insomniac-stylelint.svg?style=flat-square

[david-url]: https://david-dm.org/stormwarning/insomniac-stylelint

[david-img]: https://img.shields.io/david/stormwarning/insomniac-stylelint.svg?style=flat-square

[travis-url]: https://travis-ci.org/stormwarning/insomniac-stylelint

[travis-img]: https://img.shields.io/travis/stormwarning/insomniac-stylelint.svg?style=flat-square

[issues-url]: https://github.com/stormwarning/insomniac-stylelint/issues

[issues-img]: https://img.shields.io/github/issues/stormwarning/insomniac-stylelint.svg?style=flat-square

[stylelint]: https://github.com/stylelint/stylelint

[recess]: https://github.com/twitter/recess/blob/29bccc870b7b4ccaa0a138e504caf608a6606b59/lib/lint/strict-property-order.js

[did]: https://github.com/twbs/bootstrap/blob/f58997a0dae54dc98d11892afef9acb85bdc6a1e/.scss-lint.yml#L136

[does]: https://github.com/twbs/bootstrap/blob/ba878eb542ab6c04786741569ba089d02e9bea46/.stylelintrc#L36

[mdo-order]: http://markdotto.com/2011/11/29/css-property-order/
