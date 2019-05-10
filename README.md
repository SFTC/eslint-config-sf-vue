# SF Vue - ESLint With VUE && Prettier
[![npm][npm-image]][npm-url]
[![downloads][downloads-image]][downloads-url]

[npm-image]: https://img.shields.io/npm/v/eslint-config-sf-vue.svg
[npm-url]: https://npmjs.org/package/eslint-config-sf-vue
[downloads-image]: https://img.shields.io/npm/dm/eslint-config-sf-vue.svg
[downloads-url]: https://npmjs.org/package/eslint-config-sf-vue

## Install

```bash
npm install eslint-config-sf-vue
```

## Usage
The config is based on `eslint-config-airbnb-base` and `eslint-plugin-vue` and `eslint-config-prettier`.

Then, add this to your .eslintrc file:

```
{
  "extends": ["sf-vue"]
}
```
Tip: to check your .vue/\.html/\.js，you need to edit your editor's perference.
Eg. in my vs:
```
"eslint.autoFixOnSave": true,  //  启用保存时自动修复,默认只支持.js文件
"eslint.validate": [
  "javascript",  //  用eslint的规则检测js文件
  {
    "language": "vue",   // 检测vue文件
    "autoFix": true   //  为vue文件开启保存自动修复的功能
  },
  {
    "language": "html",
    "autoFix": true
  },
],
```
## Docs
[doc.md](./doc.md)

## Learn more
For the full listing of rules, editor plugins, FAQs, and more, visit the main<br />
[Airbnb JavaScript Style repo](https://github.com/airbnb/javascript).<br />
[Airbnb Vue Style repo](https://eslint.vuejs.org/rules).<br />
[Airbnb Prettier repo](https://prettier.io/docs/en/integrating-with-linters.html).<br />

## License
MIT