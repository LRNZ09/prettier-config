# @lrnz09/prettier-config

This is a Prettier configuration file that enforces consistent code formatting in your JavaScript and JSX files. It includes the following rules:

```js
{
  jsxSingleQuote: true,
  semi: false,
  singleQuote: true,
  trailingComma: 'all',
};
```

## Installation

To use this Prettier configuration in your project, follow these steps:

1. **Install Prettier**: If you haven't already, you need to install Prettier as a development dependency in your project, along with this config. For example, with `npm`:

   ```bash
   npm install --save-dev prettier @lrnz09/prettier-config
   ```

2. **Configuration File**: Create a Prettier configuration file in your project's root directory and name it `prettier.config.js`. Set the configuration to use the `@lrnz09/prettier-config` package:

   ```js
   module.exports = '@lrnz09/prettier-config'
   ```

## Usage

With this configuration in place, you can now format your code using Prettier.

Follow the official docs [here](https://prettier.io/docs/en/).
