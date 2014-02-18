wechatface
=====

This library allows the handling and conversion of Wechat Face in `Javascript`.

## Usage

### Browser

```html
<link href="./wechatface.css" rel="stylesheet" type="text/css" />
<script src="./jquery.js"></script>
<script src="./wechatface.js"></script>
```

```js
$('.message').html(wechatFace.faceToHTML(MSG));
```

#### Seajs

```js
seajs.config({
  alias: {
    wechatface: 'https://raw.github.com/leeeboo/wechatface/master/wechatface.js'
  }
});

seajs.use(['wechatface'], function (wechatface) {
  // TODO
});
// or
define('test', function (require, exports, modules) {
  var wechatface = require('wechatface');
});
```

#### RequireJS (AMD)

```js
require.config({
  paths: {
    wechatface: 'https://raw.github.com/leeeboo/wechatface/master/wechatface.js'
  }
});

require(['wechatface'], function (wechatface) {
  // TODO
});
```

## License

(The MIT License)

Copyright (c) 2012 - 2014 Albert <lb13810398408@gmail.com>.

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

