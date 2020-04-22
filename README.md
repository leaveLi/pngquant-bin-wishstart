# pngquant-bin-local-install

## 基于 pngquant-bin 安装不在需要进行翻墙

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
