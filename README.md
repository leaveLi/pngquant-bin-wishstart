# pngquant-bin-wishstart

## 基于 pngquant-bin vendor 下资源转存 wishstart

## 安装

```
$ npm install pngquant-bin
```

## 使用

```js
const execFile = require("child_process").execFile;
const pngquant = require("pngquant-bin");

execFile(pngquant, ["-o", "output.png", "input.png"], (err) => {
  console.log("Image minified!");
});
```

## CLI

```
$ npm install --global pngquant-bin
```

```
$ pngquant --help
```
