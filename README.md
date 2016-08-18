# css-skins 0.0.6

Css module of single purpose classes for skins

#### Stats

2334 | 289 | 289
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-skins
```

#### With Git

```
git clone https://github.com/tachyons-css/css-skins
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-skins";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-skins">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   SKINS
*/
/* Grays */
.blk { color: near-black; }
.dk-gry { color: dark-gray; }
.md-gry { color: mid-gray; }
.gray { color: gray; }
.silver { color: silver; }
.lt-slvr { color: light-silver; }
.lt-gry { color: light-gray; }
.near-wht { color: near-white; }
.wht { color: white; }
/* Text colors */
.pink { color: pink; }
.lightpink { color: lightpink; }
.hotpink { color: hotpink; }
.deeppink { color: deeppink; }
.palevioletred { color: palevioletred; }
.mediumvioletred { color: mediumvioletred; }
.lightsalmon { color: lightsalmon; }
.salmon { color: salmon; }
.darksalmon { color: darksalmon; }
.lightcoral { color: lightcoral; }
.indianred { color: indianred; }
.crimson { color: crimson; }
.firebrick { color: firebrick; }
.darkred { color: darkred; }
.red { color: red; }
.orangered { color: orangered; }
.tomato { color: tomato; }
.coral { color: coral; }
.darkorange { color: darkorange; }
.orange { color: orange; }
.gold { color: gold; }
.yellow { color: yellow; }
.lightyellow { color: lightyellow; }
.lemonchiffon { color: lemonchiffon; }
.lightgoldenrodyellow { color: lightgoldenrodyellow; }
.papayawhip { color: papayawhip; }
.moccasin { color: moccasin; }
.peachpuff { color: peachpuff; }
.palegoldenrod { color: palegoldenrod; }
.khaki { color: khaki; }
.darkkhaki { color: darkkhaki; }
.cornsilk { color: cornsilk; }
.blanchedalmond { color: blanchedalmond; }
.bisque { color: bisque; }
.navajowhite { color: navajowhite; }
.wheat { color: wheat; }
.burlywood { color: burlywood; }
.tan { color: tan; }
.rosybrown { color: rosybrown; }
.sandybrown { color: sandybrown; }
.goldenrod { color: goldenrod; }
.darkgoldenrod { color: darkgoldenrod; }
.peru { color: peru; }
.chocolate { color: chocolate; }
.saddlebrown { color: saddlebrown; }
.sienna { color: sienna; }
.brown { color: brown; }
.maroon { color: maroon; }
.darkolivegreen { color: darkolivegreen; }
.olive { color: olive; }
.olivedrab { color: olivedrab; }
.yellowgreen { color: yellowgreen; }
.limegreen { color: limegreen; }
.lime { color: lime; }
.lawngreen { color: lawngreen; }
.chartreuse { color: chartreuse; }
.greenyellow { color: greenyellow; }
.springgreen { color: springgreen; }
.mediumspringgreen { color: mediumspringgreen; }
.lightgreen { color: lightgreen; }
.palegreen { color: palegreen; }
.darkseagreen { color: darkseagreen; }
.mediumseagreen { color: mediumseagreen; }
.seagreen { color: seagreen; }
.forestgreen { color: forestgreen; }
.green { color: green; }
.darkgreen { color: darkgreen; }
.mediumaquamarine { color: mediumaquamarine; }
.aqua { color: aqua; }
.cyan { color: cyan; }
.lightcyan { color: lightcyan; }
.paleturquoise { color: paleturquoise; }
.aquamarine { color: aquamarine; }
.turquoise { color: turquoise; }
.mediumturquoise { color: mediumturquoise; }
.darkturquoise { color: darkturquoise; }
.lightseagreen { color: lightseagreen; }
.cadetblue { color: cadetblue; }
.darkcyan { color: darkcyan; }
.teal { color: teal; }
.lightsteelblue { color: lightsteelblue; }
.powderblue { color: powderblue; }
.lightblue { color: lightblue; }
.skyblue { color: skyblue; }
.lightskyblue { color: lightskyblue; }
.deepskyblue { color: deepskyblue; }
.dodgerblue { color: dodgerblue; }
.cornflowerblue { color: cornflowerblue; }
.steelblue { color: steelblue; }
.royalblue { color: royalblue; }
.blue { color: blue; }
.mediumblue { color: mediumblue; }
.darkblue { color: darkblue; }
.navy { color: navy; }
.midnightblue { color: midnightblue; }
.lavender { color: lavender; }
.thistle { color: thistle; }
.plum { color: plum; }
.violet { color: violet; }
.orchid { color: orchid; }
.fuchsia { color: fuchsia; }
.magenta { color: magenta; }
.mediumorchid { color: mediumorchid; }
.mediumpurple { color: mediumpurple; }
.blueviolet { color: blueviolet; }
.darkviolet { color: darkviolet; }
.darkorchid { color: darkorchid; }
.darkmagenta { color: darkmagenta; }
.purple { color: purple; }
.indigo { color: indigo; }
.darkslateblue { color: darkslateblue; }
.slateblue { color: slateblue; }
.mediumslateblue { color: mediumslateblue; }
.white { color: white; }
.snow { color: snow; }
.honeydew { color: honeydew; }
.mintcream { color: mintcream; }
.azure { color: azure; }
.aliceblue { color: aliceblue; }
.ghostwhite { color: ghostwhite; }
.whitesmoke { color: whitesmoke; }
.seashell { color: seashell; }
.beige { color: beige; }
.oldlace { color: oldlace; }
.floralwhite { color: floralwhite; }
.ivory { color: ivory; }
.antiquewhite { color: antiquewhite; }
.linen { color: linen; }
.lavenderblush { color: lavenderblush; }
.mistyrose { color: mistyrose; }
.gainsboro { color: gainsboro; }
.lightgray { color: lightgray; }
.silver { color: silver; }
.darkgray { color: darkgray; }
.gray { color: gray; }
.dimgray { color: dimgray; }
.lightslategray { color: lightslategray; }
.slategray { color: slategray; }
.darkslategray { color: darkslategray; }
.black { color: black; }
/* Background Skins */
.bg-pink { background-color: pink; }
.bg-lightpink { background-color: lightpink; }
.bg-hotpink { background-color: hotpink; }
.bg-deeppink { background-color: deeppink; }
.bg-palevioletred { background-color: palevioletred; }
.bg-mediumvioletred { background-color: mediumvioletred; }
.bg-lightsalmon { background-color: lightsalmon; }
.bg-salmon { background-color: salmon; }
.bg-darksalmon { background-color: darksalmon; }
.bg-lightcoral { background-color: lightcoral; }
.bg-indianred { background-color: indianred; }
.bg-crimson { background-color: crimson; }
.bg-firebrick { background-color: firebrick; }
.bg-darkred { background-color: darkred; }
.bg-red { background-color: red; }
.bg-orangered { background-color: orangered; }
.bg-tomato { background-color: tomato; }
.bg-coral { background-color: coral; }
.bg-darkorange { background-color: darkorange; }
.bg-orange { background-color: orange; }
.bg-gold { background-color: gold; }
.bg-yellow { background-color: yellow; }
.bg-lightyellow { background-color: lightyellow; }
.bg-lemonchiffon { background-color: lemonchiffon; }
.bg-lightgoldenrodyellow { background-color: lightgoldenrodyellow; }
.bg-papayawhip { background-color: papayawhip; }
.bg-moccasin { background-color: moccasin; }
.bg-peachpuff { background-color: peachpuff; }
.bg-palegoldenrod { background-color: palegoldenrod; }
.bg-khaki { background-color: khaki; }
.bg-darkkhaki { background-color: darkkhaki; }
.bg-cornsilk { background-color: cornsilk; }
.bg-blanchedalmond { background-color: blanchedalmond; }
.bg-bisque { background-color: bisque; }
.bg-navajowhite { background-color: navajowhite; }
.bg-wheat { background-color: wheat; }
.bg-burlywood { background-color: burlywood; }
.bg-tan { background-color: tan; }
.bg-rosybrown { background-color: rosybrown; }
.bg-sandybrown { background-color: sandybrown; }
.bg-goldenrod { background-color: goldenrod; }
.bg-darkgoldenrod { background-color: darkgoldenrod; }
.bg-peru { background-color: peru; }
.bg-chocolate { background-color: chocolate; }
.bg-saddlebrown { background-color: saddlebrown; }
.bg-sienna { background-color: sienna; }
.bg-brown { background-color: brown; }
.bg-maroon { background-color: maroon; }
.bg-darkolivegreen { background-color: darkolivegreen; }
.bg-olive { background-color: olive; }
.bg-olivedrab { background-color: olivedrab; }
.bg-yellowgreen { background-color: yellowgreen; }
.bg-limegreen { background-color: limegreen; }
.bg-lime { background-color: lime; }
.bg-lawngreen { background-color: lawngreen; }
.bg-chartreuse { background-color: chartreuse; }
.bg-greenyellow { background-color: greenyellow; }
.bg-springgreen { background-color: springgreen; }
.bg-mediumspringgreen { background-color: mediumspringgreen; }
.bg-lightgreen { background-color: lightgreen; }
.bg-palegreen { background-color: palegreen; }
.bg-darkseagreen { background-color: darkseagreen; }
.bg-mediumseagreen { background-color: mediumseagreen; }
.bg-seagreen { background-color: seagreen; }
.bg-forestgreen { background-color: forestgreen; }
.bg-green { background-color: green; }
.bg-darkgreen { background-color: darkgreen; }
.bg-mediumaquamarine { background-color: mediumaquamarine; }
.bg-aqua { background-color: aqua; }
.bg-cyan { background-color: cyan; }
.bg-lightcyan { background-color: lightcyan; }
.bg-paleturquoise { background-color: paleturquoise; }
.bg-aquamarine { background-color: aquamarine; }
.bg-turquoise { background-color: turquoise; }
.bg-mediumturquoise { background-color: mediumturquoise; }
.bg-darkturquoise { background-color: darkturquoise; }
.bg-lightseagreen { background-color: lightseagreen; }
.bg-cadetblue { background-color: cadetblue; }
.bg-darkcyan { background-color: darkcyan; }
.bg-teal { background-color: teal; }
.bg-lightsteelblue { background-color: lightsteelblue; }
.bg-powderblue { background-color: powderblue; }
.bg-lightblue { background-color: lightblue; }
.bg-skyblue { background-color: skyblue; }
.bg-lightskyblue { background-color: lightskyblue; }
.bg-deepskyblue { background-color: deepskyblue; }
.bg-dodgerblue { background-color: dodgerblue; }
.bg-cornflowerblue { background-color: cornflowerblue; }
.bg-steelblue { background-color: steelblue; }
.bg-royalblue { background-color: royalblue; }
.bg-blue { background-color: blue; }
.bg-mediumblue { background-color: mediumblue; }
.bg-darkblue { background-color: darkblue; }
.bg-navy { background-color: navy; }
.bg-midnightblue { background-color: midnightblue; }
.bg-lavender { background-color: lavender; }
.bg-thistle { background-color: thistle; }
.bg-plum { background-color: plum; }
.bg-violet { background-color: violet; }
.bg-orchid { background-color: orchid; }
.bg-fuchsia { background-color: fuchsia; }
.bg-magenta { background-color: magenta; }
.bg-mediumorchid { background-color: mediumorchid; }
.bg-mediumpurple { background-color: mediumpurple; }
.bg-blueviolet { background-color: blueviolet; }
.bg-darkviolet { background-color: darkviolet; }
.bg-darkorchid { background-color: darkorchid; }
.bg-darkmagenta { background-color: darkmagenta; }
.bg-purple { background-color: purple; }
.bg-indigo { background-color: indigo; }
.bg-darkslateblue { background-color: darkslateblue; }
.bg-slateblue { background-color: slateblue; }
.bg-mediumslateblue { background-color: mediumslateblue; }
.bg-white { background-color: white; }
.bg-snow { background-color: snow; }
.bg-honeydew { background-color: honeydew; }
.bg-mintcream { background-color: mintcream; }
.bg-azure { background-color: azure; }
.bg-aliceblue { background-color: aliceblue; }
.bg-ghostwhite { background-color: ghostwhite; }
.bg-whitesmoke { background-color: whitesmoke; }
.bg-seashell { background-color: seashell; }
.bg-beige { background-color: beige; }
.bg-oldlace { background-color: oldlace; }
.bg-floralwhite { background-color: floralwhite; }
.bg-ivory { background-color: ivory; }
.bg-antiquewhite { background-color: antiquewhite; }
.bg-linen { background-color: linen; }
.bg-lavenderblush { background-color: lavenderblush; }
.bg-mistyrose { background-color: mistyrose; }
.bg-gainsboro { background-color: gainsboro; }
.bg-lightgray { background-color: lightgray; }
.bg-silver { background-color: silver; }
.bg-darkgray { background-color: darkgray; }
.bg-gray { background-color: gray; }
.bg-dimgray { background-color: dimgray; }
.bg-lightslategray { background-color: lightslategray; }
.bg-slategray { background-color: slategray; }
.bg-darkslategray { background-color: darkslategray; }
.bg-black { background-color: black; }
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
