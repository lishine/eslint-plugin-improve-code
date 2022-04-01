# eslint-plugin-eslint-improve-code

created in order to add rule: when arrow func one line breaks, convert it to return style

## Installation

You'll first need to install [ESLint](https://eslint.org/):

```sh
npm i eslint --save-dev
```

Next, install `eslint-plugin-eslint-improve-code`:

```sh
npm install eslint-plugin-eslint-improve-code --save-dev
```

## Usage

Add `eslint-improve-code` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "eslint-improve-code"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "eslint-improve-code/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here


