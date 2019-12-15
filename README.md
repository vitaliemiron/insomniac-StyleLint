# Insomniac\* StyleLint

[![npm version][npm-img]][npm-url]
[![npm downloads][npm-dls]][npm-url]
[![dependency status][david-img]][david-url]
[![build status][travis-img]][travis-url]
[![github issues][issues-img]][issues-url]

A [Stylelint][] config that sorts CSS properties the way [Recess][] did and
Bootstrap [did][]/[does][].

Stylelint is a tool that reports bad code in your CSS files. It helps to enforce the consistent code and prevents you from making errors in your stylesheets. It is highly configurable. 

\*With some modifications & additions for modern properties.

## Sort config
![Alt Text](https://raw.githubusercontent.com/vitaliemiron/insomniac-styleLint/readme/img/order.gif)

## Syntax checker
![Alt Text](https://raw.githubusercontent.com/vitaliemiron/insomniac-styleLint/readme/img/syntax.gif)

## Usage

1.  Add [stylelint][] and this package to your project:  
    ```sh
    npm install --save-dev stylelint insomniac-stylelint
    ```

2. Add file .stylelintrc.json in root of your theme

3.  Configure your stylelint configuration file to extend this package:  
    ```js
    {
      "extends": "insomniac-stylelint",
      "rules": {
        // Add overrides and additional rules here
      }
    }
    ```

## Visual Studio Code

Install [VSCode-extension][] stylelint.


## References

[@mdo on CSS Property Order][mdo-order]

[npm-url]: https://www.npmjs.com/package/insomniac-stylelint

[npm-img]: https://img.shields.io/npm/v/insomniac-stylelint.svg?style=flat-square

[npm-dls]: https://img.shields.io/npm/dt/insomniac-stylelint.svg?style=flat-square

[david-url]: https://david-dm.org/vitaliemiron/insomniac-stylelint

[david-img]: https://img.shields.io/david/vitaliemiron/insomniac-stylelint.svg?style=flat-square

[travis-url]: https://travis-ci.org/vitaliemiron/insomniac-stylelint

[travis-img]: https://img.shields.io/travis/vitaliemiron/insomniac-stylelint.svg?style=flat-square

[issues-url]: https://github.com/vitaliemiron/insomniac-stylelint/issues

[issues-img]: https://img.shields.io/github/issues/vitaliemiron/insomniac-stylelint.svg?style=flat-square

[stylelint]: https://github.com/stylelint/stylelint

[recess]: https://github.com/twitter/recess/blob/29bccc870b7b4ccaa0a138e504caf608a6606b59/lib/lint/strict-property-order.js

[did]: https://github.com/twbs/bootstrap/blob/f58997a0dae54dc98d11892afef9acb85bdc6a1e/.scss-lint.yml#L136

[does]: https://github.com/twbs/bootstrap/blob/ba878eb542ab6c04786741569ba089d02e9bea46/.stylelintrc#L36

[mdo-order]: http://markdotto.com/2011/11/29/css-property-order/

[VSCode-extension]: https://marketplace.visualstudio.com/items?itemName=thibaudcolas.stylelint