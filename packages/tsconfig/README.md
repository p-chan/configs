# tsconfig

> Shared TypeScript config for [@p-chan](https://github.com/p-chan)

## Install

```bash
$ npm install @p-chan/tsconfig --save-dev
```

## Usage

Edit `tsconfig.json`.

```jsonc
{
  "extends": "@p-chan/tsconfig"
}
```

### Override

```jsonc
{
  "extends": "@p-chan/tsconfig",
  "compilerOptions": {
    "outDir": "./dist",
    "baseUrl": "./"
  }
}
```

## Author

[@p-chan](https://github.com/p-chan)

## License

MIT

---

Inspired by [sindresorhus/tsconfig](https://github.com/sindresorhus/tsconfig)
