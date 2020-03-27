# JavaScript QRCode Generator, Decoder & Scanner

Here is a merged and optimized version of [Lazar's work](https://github.com/LazarSoft/jsqrcode), which is a port of [ZXing qrcode scanner](http://code.google.com/p/zxing).

## Usage

Include the scripts in your HTML:

```sh
<script type="text/javascript" src="jsqrcode.min.js"></script>
```

Set qrcode.callback to function "func(data)", where data will get the decoded information.

Decode image with: qrcode.decode(url or DataURL).
Decode from canvas with "qr-canvas" ID: qrcode.decode()

Check the code for detail usage guidance.