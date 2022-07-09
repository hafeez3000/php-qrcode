# php-qrcode examples

## Simple examples that demonstrate the different output types

- [image](./image.php): Raster images via the [GD extension](https://www.php.net/manual/de/book.image.php)
- [ImageMagick](./imagick.php): Raster Images via [ImageMagick](https://imagemagick.org/)
- [SVG](./svg.php): [Scalable Vector Graphics](https://developer.mozilla.org/en-US/docs/Web/SVG)
- [HTML](./html.php): HTML markup
- [FPDF](./fpdf.php): PDF output via [FPDF](http://www.fpdf.org/)
- [EPS](./eps.php): Encapsulated PostScript
- [String](./text.php): String output
- [QRCode Reader](./reader.php): a simple reader example


## Advanced output examples

- [Custom output](./custom_output.php): a simple example that demonstrates the usage of custom output classes
- [Interactive output](./qrcode-interactive.php): interactive demo (via [index.html](./index.html))
- [GD Image with logo](./imageWithLogo.php): a logo on top of the QR Code
- [GD image with text](./imageWithText.php): description text under the QR Code
- [SVG with logo](./svgWithLogo.php): an SVG QR Code with embedded logo (that is also SVG)
- [SVG with randomly colored modules](./svgRandomColoredDots.php): a visual effect using multiple colors for the matrix modules