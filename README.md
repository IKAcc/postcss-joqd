# postcss-joqd
[![](http://ikacc.ir/github-assets/joqd-header-v1.png)](https://github.com/IKAcc/Joqd)
[Joqd UI](https://github.com/IKAcc/Joqd) only in PostCSS

## Installation
```
$ npm i -D postcss-joqd
```

## Usage
### `Configuration`

Make sure having proper configs on **postcss.config.js** :
```js
module.exports = {
    plugins: [
      require('autoprefixer'),
      require('postcss-import')(),
      require('postcss-each')(),
      require('postcss-mixins')(),
      require('postcss-nested')(),
      require('postcss-at-rules-variables')(),
      require('postcss-for')(),
      require('postcss-custom-properties')(),
      require('postcss-simple-vars')(),
      require('postcss-short')(),
      require('postcss-calc')(),
      require('postcss-color-function')()
    ]
}
```

### `Import`
Import `../../node_modules/postcss-joqd/__vars.css`, `../../node_modules/postcss-joqd/__mixins.css` and `../../node_modules/postcss-joqd/joqd.css` sequentially to your main CSS file.

**note**: *don't forget to set up your fonts*
