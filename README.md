# md-country-select

[![Build Status](https://travis-ci.org/davidhavard/md-country-select.svg?branch=master)](https://travis-ci.org/davidhavard/md-country-select)

Angular module to generate an angular-material select list of countries using country codes in the
[ISO 3166-1 standard](https://en.wikipedia.org/wiki/ISO_3166-1).

Adapted from [ng-country-select](https://github.com/navinpeiris/ng-country-select)


## Usage

Add `mdCountrySelect` as a dependency for your app:

```javascript
angular.module('myApp', ['...', 'mdCountrySelect', '...'])
```

Simple usage to get a list of countries:

```html
<md-country-select></md-country-select>
```

Supplying priority countries to be placed at the top of the list:

```html
<md-country-select cs-priorities="AU, DE, GB, US"></md-country-select>
```

Supplying only certain countries:

```html
<md-country-select cs-only="AU, DE, GB, US"></md-country-select>
```

Discarding certain countries:

```html
<md-country-select cs-except="AU, DE, GB, US"></md-country-select>
```

Making the selection mandatory by removing the empty option:

```html
<md-country-select cs-required></md-country-select>
```

## License

The MIT License

Copyright (c) 2015 Navin Peiris http://navinpeiris.com

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
