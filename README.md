# insomniac-stylelint

Insomniac StyleLint extensible and sharable configuration.

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