# Sass Property Order

> Sass property ordering tool.

It supports only sass syntax.

This package was taken from [SortSass](https://github.com/miraks/sort-sass) created by [Alexey Volodkin](https://github.com/miraks). The only difference is the order of the sass properties.

## Install

```sh
npm install -g sort-sass
```

Leave off the `-g` if you don't wish to install globally.

## Usage

From CLI:
```sh
sortsass /path/to/styles.sass
```

From node:
```js
var fs = require('fs');
var sortSass = require('sort-sass');

var sassString = fs.readFileSync('some.sass');
var sortedSassString = sortSass(sassString);
```

## License

MIT © [Alexey Volodkin](a@vldkn.net)
