# eslint-plugin-eslint-no-invalid-this-except

The same as eslint-no-invalid-this, except checking sepcified functions

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-eslint-no-invalid-this-except`:

```
$ npm install eslint-plugin-eslint-no-invalid-this-except --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-eslint-no-invalid-this-except` globally.

## Usage

Add `eslint-no-invalid-this-except` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "eslint-no-invalid-this-except"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "eslint-no-invalid-this-except/rule-name": 2
    }
}
```

## Supported Rules

* Fill in provided rules here





