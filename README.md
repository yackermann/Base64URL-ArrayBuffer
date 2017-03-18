# Base64URL-ArrayBuffer

[![Build Status](https://travis-ci.org/herrjemand/Base64URL-ArrayBuffer.svg?branch=master)](https://travis-ci.org/herrjemand/Base64URL-ArrayBuffer)

Encode/decode Base64URL data into ArrayBuffers

Based on original [base64-arraybuffer](https://github.com/niklasvh/base64-arraybuffer) by [@niklasvh](https://github.com/niklasvh)

## Getting Started:

TODO:

 - Submit to NPM
 - Submit to CDNJS

## 

The library encodes and decodes Base64URL to and from ArrayBuffers

### Node.js/AMD
 - __encode(buffer)__ - Encodes `ArrayBuffer` into Base64URL string
 - __decode(str)__ - Decodes Base64URL string to `ArrayBuffer`

### Browser

Just add `<script src="base64url-arraybuffer.js"></script>` to your HTML file.

 - __window.base64url.encode(buffer)__ - Encodes `ArrayBuffer` into Base64URL string
 - __window.base64url.decode(str)__ - Decodes Base64URL string to `ArrayBuffer`

## License

Copyright (c) 2017 Yuriy Ackermann

Copyright (c) 2012 Niklas von Hertzen

Licensed under the MIT license.
