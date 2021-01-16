# prettier-config

> Shareable Prettier config for [@p-chan](https://github.com/p-chan)

## Install

```bash
$ npm install @p-chan/prettier-config --save-dev
```

## Usage

Edit `.prettierrc`.

```json
"@p-chan/prettier-config"
```

## Override

Edit `.prettierrc.js`.

```js
module.exports = {
  ...require('@p-chan/prettier-config'),
  printWidth: 80,
  semi: true,
  singleQuote: false,
}
```

## Author

[@p-chan](https://github.com/p-chan)

## License

MIT

---

Inspired by [azz/prettier-config](https://github.com/azz/prettier-config)
