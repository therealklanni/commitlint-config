# commitlint-config

A [commitlint](https://commitlint.js.org) config that extends `@commitlint/config-conventional`. Additionally enforces a body line length max of 72 characters.

## Usage

```bash
npm install --save-dev husky @commitlint/{config-conventional,cli} @therealklanni/commitlint-config
```

In your `commitlint.config.js` update the `extends` field:

```js
module.exports = {
  extends: ['@therealklanni]
}
```
