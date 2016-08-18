# css-filter-hue-rotate 0.0.7

Css module of single purpose classes for filter hue rotate

#### Stats

285 | 32 | 32
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-filter-hue-rotate
```

#### With Git

```
git clone https://github.com/tachyons-css/css-filter-hue-rotate
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-filter-hue-rotate";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-filter-hue-rotate">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FILTER HUE ROTATE
*/
.hue-rotate1 { filter: hue-rotate( 45deg ); }
.hue-rotate2 { filter: hue-rotate( 90deg ); }
.hue-rotate3 { filter: hue-rotate( 135deg ); }
.hue-rotate4 { filter: hue-rotate( 180deg ); }
.hue-rotate5 { filter: hue-rotate( 225deg ); }
.hue-rotate6 { filter: hue-rotate( 270deg ); }
.hue-rotate7 { filter: hue-rotate( 315deg ); }
.hue-rotate8 { filter: hue-rotate( 360deg ); }
@media screen and (min-width: 48em) {
 .hue-rotate1-ns { filter: hue-rotate( 45deg ); }
 .hue-rotate2-ns { filter: hue-rotate( 90deg ); }
 .hue-rotate3-ns { filter: hue-rotate( 135deg ); }
 .hue-rotate4-ns { filter: hue-rotate( 180deg ); }
 .hue-rotate5-ns { filter: hue-rotate( 225deg ); }
 .hue-rotate6-ns { filter: hue-rotate( 270deg ); }
 .hue-rotate7-ns { filter: hue-rotate( 315deg ); }
 .hue-rotate8-ns { filter: hue-rotate( 360deg ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .hue-rotate1-m { filter: hue-rotate( 45deg ); }
 .hue-rotate2-m { filter: hue-rotate( 90deg ); }
 .hue-rotate3-m { filter: hue-rotate( 135deg ); }
 .hue-rotate4-m { filter: hue-rotate( 180deg ); }
 .hue-rotate5-m { filter: hue-rotate( 225deg ); }
 .hue-rotate6-m { filter: hue-rotate( 270deg ); }
 .hue-rotate7-m { filter: hue-rotate( 315deg ); }
 .hue-rotate8-m { filter: hue-rotate( 360deg ); }
}
@media screen and (min-width: 64em) {
 .hue-rotate1-l { filter: hue-rotate( 45deg ); }
 .hue-rotate2-l { filter: hue-rotate( 90deg ); }
 .hue-rotate3-l { filter: hue-rotate( 135deg ); }
 .hue-rotate4-l { filter: hue-rotate( 180deg ); }
 .hue-rotate5-l { filter: hue-rotate( 225deg ); }
 .hue-rotate6-l { filter: hue-rotate( 270deg ); }
 .hue-rotate7-l { filter: hue-rotate( 315deg ); }
 .hue-rotate8-l { filter: hue-rotate( 360deg ); }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
