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
[stylelint]: https://github.com/stylelint/stylelint
[did]: https://github.com/twbs/bootstrap/blob/f58997a0dae54dc98d11892afef9acb85bdc6a1e/.scss-lint.yml#L136
[does]: https://github.com/twbs/bootstrap/blob/ba878eb542ab6c04786741569ba089d02e9bea46/.stylelintrc#L36