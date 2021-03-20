# htmlToSvg

converts html div to svg images

## Install

```
$ npm install htmlsvg
```

## Usage

```js
import htmlToSvg from "htmlsvg";

const svg = await htmlToSvg("divId");
console.log(svg);
```

You can directly download svg with passing config object

```js
import htmlToSvg from "htmlsvg";

const svgConfig = {
  download: true,
  filename: "htmltosvg",
};
const svg = await htmlToSvg("divId", svgConfig);
console.log(svg);
```
