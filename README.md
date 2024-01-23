# Dipcode Prettier config

> Shareable Prettier config for Dipcode.

- [Usage](#usage)
- [Links](#links)

## Usage

The package provides Dipcode's `.prettierrc` as an extensible shared config.

Install the config

```sh
npm install --save-dev @dipcode/prettier-config
```

Then edit your `package.json`

```json
{
  // ...
  "prettier": "@company/prettier-config"
}
```

If you want to extend the configuration, you have to create your own `.prettierrc.js`.

```js
import companyPrettierConfig from '@dipcode/prettier-config';

export default {
  ...dipcodePrettierConfig,
  // your override options
};
```

## Links

- [Prettier](https://prettier.io/)
