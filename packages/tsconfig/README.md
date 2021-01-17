# tsconfig

> Shareable TypeScript config for [@p-chan](https://github.com/p-chan)

## Install

```bash
$ npm install @p-chan/tsconfig --save-dev
```

## Usage

Edit `tsconfig.json`.

```jsonc
{
  // Default (use Recommended)
  "extends": "@p-chan/tsconfig",

  // Recommended
  "extends": "@p-chan/tsconfig/recommended.json",

  // for Node.js v12
  "extends": "@p-chan/tsconfig/node12.json",

  // for Node.js v14
  "extends": "@p-chan/tsconfig/node14.json",

  // for Next.js
  "extends": "@p-chan/tsconfig/next.json"
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
