# Prettier Configuration

Prettier is an opinionated code formatter that helps keep your code consistent and easy to read. This repository contains the configuration for Prettier that I use for my projects.

## Installation

To use this configuration, you will need to have Prettier installed in your project. You can install it by running the following command:

```shell
npm install --save-dev prettier
```

Then you have to install my config with the following command:

```shell
npm install --save-dev @qnton/prettier-config
```

## Usage

To use this configuration, add the following key to your `package.json` file:

```json
{
  "prettier": "@qnton/prettier-config"
}
```

## Customization

If you want to customize the configuration, you can do so by creating a `.prettierrc.js` file in the root of your project and adding your own settings. But first you have to remove the option in the `package.json`

```js
const baseConfig = require("@qnton/prettier-config");

module.exports = {
  ...baseConfig,
  //Add your config here
};
```

## Conclusion

With this configuration, you can ensure that your code is consistently formatted and easy to read. If you have any questions or issues, please feel free to open an issue in this repository.
