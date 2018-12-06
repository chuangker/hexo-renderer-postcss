# hexo-renderer-postcss2

A Hexo plugin for rendering PostCSS

## Install

``` bash
$ npm install hexo-renderer-postcss2 --save
```

## Options

You can create `.postcssrc.js`:

``` js
module.exports = {
  plugins: {
    autoprefixer: {
      browsers: ['last 4 version']
    }
  }
}
```