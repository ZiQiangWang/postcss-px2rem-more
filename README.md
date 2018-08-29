# postcss-px2rem-more
postcss plugin for px2rem-more

Based on [postcss-px2rem](https://www.npmjs.com/package/postcss-px2rem) and [px2rem-more](https://github.com/ZiQiangWang/px2rem) added the exclude folder option.

Not convert **font-size** by default，you can enable it by setting `keepFontSize=false`

[![Downloads][downloads-image]][downloads-url]

[downloads-image]: https://img.shields.io/npm/dm/postcss-px2rem-exclude.svg?style=flat-square
[downloads-url]: https://www.npmjs.com/package/postcss-px2rem-exclude

## Useage

### .postcssrc.js
```javascript
module.exports = {
  'plugins': {
    'postcss-px2rem-more': {
      remUnit: 75,
      exclude: /node_modules|folder_name/i
    }
  }
}
```
