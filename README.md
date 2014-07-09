# CSS COLUMN FILL

  Mobile-first classes for css-column-fill.
  Set the desired css-column-fill on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-column-fill
```
or download the css on github and include in your project.

## File Size


## The Code
```
.cf-auto    { column-fill: auto; }
.cf-balance { column-fill: balance; }
.cf-i       { column-fill: inherit; }

@include break(not-small) {
  .cf-auto-ns    { column-fill: auto; }
  .cf-balance-ns { column-fill: balance; }
  .cf-i-ns       { column-fill: inherit; }
}

@include break(medium) {
  .cf-auto-m    { column-fill: auto; }
  .cf-balance-m { column-fill: balance; }
  .cf-i-m       { column-fill: inherit; }
}

@include break(large) {
  .cf-auto-l    { column-fill: auto; }
  .cf-balance-l { column-fill: balance; }
  .cf-i-l       { column-fill: inherit; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

