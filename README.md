# css-filter-hue-rotate 1.0.6

Css module of single purpose classes for filter hue rotate

#### Stats

331 | 32 | 64
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-filter-hue-rotate
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-filter-hue-rotate
```

ssh:
```
git clone git@github.com:tachyons-css/css-filter-hue-rotate.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-filter-hue-rotate";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-filter-hue-rotate@1.0.6/css/css-filter-hue-rotate.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-filter-hue-rotate">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FILTER HUE ROTATE
*/
.hue-rotate1 { -webkit-filter: hue-rotate( 45deg ); filter: hue-rotate( 45deg ); }
.hue-rotate2 { -webkit-filter: hue-rotate( 90deg ); filter: hue-rotate( 90deg ); }
.hue-rotate3 { -webkit-filter: hue-rotate( 135deg ); filter: hue-rotate( 135deg ); }
.hue-rotate4 { -webkit-filter: hue-rotate( 180deg ); filter: hue-rotate( 180deg ); }
.hue-rotate5 { -webkit-filter: hue-rotate( 225deg ); filter: hue-rotate( 225deg ); }
.hue-rotate6 { -webkit-filter: hue-rotate( 270deg ); filter: hue-rotate( 270deg ); }
.hue-rotate7 { -webkit-filter: hue-rotate( 315deg ); filter: hue-rotate( 315deg ); }
.hue-rotate8 { -webkit-filter: hue-rotate( 360deg ); filter: hue-rotate( 360deg ); }
@media screen and (min-width: 48em) {
 .hue-rotate1-ns { -webkit-filter: hue-rotate( 45deg ); filter: hue-rotate( 45deg ); }
 .hue-rotate2-ns { -webkit-filter: hue-rotate( 90deg ); filter: hue-rotate( 90deg ); }
 .hue-rotate3-ns { -webkit-filter: hue-rotate( 135deg ); filter: hue-rotate( 135deg ); }
 .hue-rotate4-ns { -webkit-filter: hue-rotate( 180deg ); filter: hue-rotate( 180deg ); }
 .hue-rotate5-ns { -webkit-filter: hue-rotate( 225deg ); filter: hue-rotate( 225deg ); }
 .hue-rotate6-ns { -webkit-filter: hue-rotate( 270deg ); filter: hue-rotate( 270deg ); }
 .hue-rotate7-ns { -webkit-filter: hue-rotate( 315deg ); filter: hue-rotate( 315deg ); }
 .hue-rotate8-ns { -webkit-filter: hue-rotate( 360deg ); filter: hue-rotate( 360deg ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .hue-rotate1-m { -webkit-filter: hue-rotate( 45deg ); filter: hue-rotate( 45deg ); }
 .hue-rotate2-m { -webkit-filter: hue-rotate( 90deg ); filter: hue-rotate( 90deg ); }
 .hue-rotate3-m { -webkit-filter: hue-rotate( 135deg ); filter: hue-rotate( 135deg ); }
 .hue-rotate4-m { -webkit-filter: hue-rotate( 180deg ); filter: hue-rotate( 180deg ); }
 .hue-rotate5-m { -webkit-filter: hue-rotate( 225deg ); filter: hue-rotate( 225deg ); }
 .hue-rotate6-m { -webkit-filter: hue-rotate( 270deg ); filter: hue-rotate( 270deg ); }
 .hue-rotate7-m { -webkit-filter: hue-rotate( 315deg ); filter: hue-rotate( 315deg ); }
 .hue-rotate8-m { -webkit-filter: hue-rotate( 360deg ); filter: hue-rotate( 360deg ); }
}
@media screen and (min-width: 64em) {
 .hue-rotate1-l { -webkit-filter: hue-rotate( 45deg ); filter: hue-rotate( 45deg ); }
 .hue-rotate2-l { -webkit-filter: hue-rotate( 90deg ); filter: hue-rotate( 90deg ); }
 .hue-rotate3-l { -webkit-filter: hue-rotate( 135deg ); filter: hue-rotate( 135deg ); }
 .hue-rotate4-l { -webkit-filter: hue-rotate( 180deg ); filter: hue-rotate( 180deg ); }
 .hue-rotate5-l { -webkit-filter: hue-rotate( 225deg ); filter: hue-rotate( 225deg ); }
 .hue-rotate6-l { -webkit-filter: hue-rotate( 270deg ); filter: hue-rotate( 270deg ); }
 .hue-rotate7-l { -webkit-filter: hue-rotate( 315deg ); filter: hue-rotate( 315deg ); }
 .hue-rotate8-l { -webkit-filter: hue-rotate( 360deg ); filter: hue-rotate( 360deg ); }
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

