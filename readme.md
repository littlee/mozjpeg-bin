# mozjpeg-mirror

use https://npm.taobao.org/mirrors/mozjpeg-bin/ as downlaod source

# mozjpeg-bin [![Build Status](https://travis-ci.org/imagemin/mozjpeg-bin.svg?branch=master)](http://travis-ci.org/imagemin/mozjpeg-bin)

> [mozjpeg](https://github.com/mozilla/mozjpeg) is a production-quality JPEG encoder that improves compression while maintaining compatibility with the vast majority of deployed decoders

You probably want [`imagemin-mozjpeg`](https://github.com/imagemin/imagemin-mozjpeg) instead.


## Install

```
$ npm install mozjpeg-mirror
```


## Usage

```js
const {execFile} = require('child_process');
const mozjpeg = require('mozjpeg-mirror');

execFile(mozjpeg, ['-outfile', 'output.jpg', 'input.jpg'], err => {
	console.log('Image minified!');
});
```


## CLI

```
$ npm install --global mozjpeg-mirror
```

```
$ mozjpeg --help
```


## License

MIT © [Imagemin](https://github.com/imagemin)
