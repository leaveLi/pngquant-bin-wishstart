# pngquant-bin-wishstart

## 安装

```
$ npm install pngquant-bin-wishstart
```

## 使用

```js
const { execFile } = require("child_process");
const pngquant = require("pngquant-bin-wishstart");

execFile(pngquant, ["-o", "output.png", "input.png"], (err) => {
  console.log("Image minified!");
});
```

## CLI

```
$ npm install --global pngquant-bin-wishstart
```

```
$ pngquant --help
```
