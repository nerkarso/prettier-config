# @nerkarso/prettier-config

Prettier configuration.

## Installation

```sh
npm install -D https://github.com/nerkarso/prettier-config.git
```

## Usage

Add a key in your **package.json** file.

```json
"prettier": "@nerkarso/prettier-config"
```

Or create a **.prettierrc** file and export a string.

```
@nerkarso/prettier-config
```

Or create a **prettier.config.js** file and export an object.

```js
module.exports = {
  ...require('@nerkarso/prettier-config'),
  // Properties to be overwritten
};
```

## License

[MIT](LICENSE)
