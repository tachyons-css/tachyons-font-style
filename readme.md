# tachyons-font-style 4.0.5

Performance based css module.

### Stats

165 | 8 | 8
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-font-style
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/tachyons-font-style
```

ssh:
```
git clone git@github.com:tachyons-css/tachyons-font-style.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-font-style";
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
<link rel="stylesheet" href="http://unpkg.com/tachyons-font-style@4.0.5/css/tachyons-font-style.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-font-style">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*

   FONT STYLE

*/
.i { font-style: italic; }
.fs-normal { font-style: normal; }
@media screen and (min-width: 30em) {
 .i-ns { font-style: italic; }
 .fs-normal-ns { font-style: normal; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .i-m { font-style: italic; }
 .fs-normal-m { font-style: normal; }
}
@media screen and (min-width: 60em) {
 .i-l { font-style: italic; }
 .fs-normal-l { font-style: normal; }
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

