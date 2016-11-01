# css-column-fill 1.0.6

Css module of single purpose classes for column fill

#### Stats

220 | 12 | 36
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-column-fill
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-column-fill
```

ssh:
```
git clone git@github.com:tachyons-css/css-column-fill.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-column-fill";
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
<link rel="stylesheet" href="http://unpkg.com/css-column-fill@1.0.6/css/css-column-fill.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-column-fill">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   COLUMN FILL
*/
.cf-auto { -webkit-column-fill: auto; -moz-column-fill: auto; column-fill: auto; }
.cf-balance { -webkit-column-fill: balance; -moz-column-fill: balance; column-fill: balance; }
.cf-i { -webkit-column-fill: inherit; -moz-column-fill: inherit; column-fill: inherit; }
@media screen and (min-width: 48em) {
 .cf-auto-ns { -webkit-column-fill: auto; -moz-column-fill: auto; column-fill: auto; }
 .cf-balance-ns { -webkit-column-fill: balance; -moz-column-fill: balance; column-fill: balance; }
 .cf-i-ns { -webkit-column-fill: inherit; -moz-column-fill: inherit; column-fill: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .cf-auto-m { -webkit-column-fill: auto; -moz-column-fill: auto; column-fill: auto; }
 .cf-balance-m { -webkit-column-fill: balance; -moz-column-fill: balance; column-fill: balance; }
 .cf-i-m { -webkit-column-fill: inherit; -moz-column-fill: inherit; column-fill: inherit; }
}
@media screen and (min-width: 64em) {
 .cf-auto-l { -webkit-column-fill: auto; -moz-column-fill: auto; column-fill: auto; }
 .cf-balance-l { -webkit-column-fill: balance; -moz-column-fill: balance; column-fill: balance; }
 .cf-i-l { -webkit-column-fill: inherit; -moz-column-fill: inherit; column-fill: inherit; }
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

