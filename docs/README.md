## Goal and Philosophy

The ideal goal is to help us deal with things that can be more precise in the simplest way. `Arya Jarvis` is an attempt to do this, it designed to save developers more time and energy.

## Prerequisites

[Node.js](https://nodejs.org/en/) (>= 8.\*), Npm version 5+ ([Yarn](https://www.jeffjade.com/2017/12/30/135-npm-vs-yarn-detial-memo/) preferred).

## Install

```bash
pnpm add -g arya-jarvis
# OR
yarn global add arya-jarvis
# OR
npm i arya-jarvis -g
```

## Usage

The following two functions can support multiple format files, such as: `.js`, `.vue`, `.ux`, `.less`, `.scss`, `.css`, `.json`, `.md`, `.html`, `.qxml`, `.wxml`.

### 💄 Prettier the code under the specified path.

```bash
arya prettier index.js
# 👏 Or Use Alias
arya p ./src/**/**/*.js
# 👍🙌 Or Use Alias & Wildcard
arya p .
```

### 🔬 Listen for code changes in the specified path and prettier them.

```bash
arya watcher index.js
# 👏 Or Use Alias
arya w ./src/**/**/*.js
# 👍🙌 Or Use Alias & Wildcard
arya w .
```

It is worth mentioning that the code formatting of this project is handled by `arya w .`. Thanks to myself for developing this `arya jarvis` in my spare time, **I am super like it**.

### 🌍 Used to quickly build a local web server.

```bash
arya server
# 👏 Or Use Alias
arya s
```

### 🌊 One-click preview of the specified Markdown file

```bash
arya markdown README.md
arya markdown ./nice-project/README.md
# 👏 Or Use Alias
arya m README.md
```

#### Watcher (`-w` , `--watch`)

By default, the `Markdown` file you specify will not be listened. You can enable the monitor function by adding the `-w` option to refresh your preview page in real time. See the example below：

```bash
arya markdown README.md -w
arya markdown README.md --watch
```

### ⚡️ Find your local IP address and print it.

```bash
arya ip
```

Regarding the request for obtaining a local IP (and public network IP), whether using Mac, Linux, or Windows users, it is quite troublesome if there is no special configuration; even if you use ipconfig or ifconfig in the console, the results obtained need Fan screening; easy access with `arya ip`.

### 👀 View programs that occupy the specified port.

```bash
arya port 8080
```

### 📷 Generate QR code for specified text

```bash
arya qrcode "https://www.jeffjade.com/"
arya qrcode "晚晴幽草轩轩主"
```

This project integrate [QR code generator](https://github.com/soldair/node-qrcod), which can be conveniently located on the console, and generates a QR code for the specified text according to the command, and provides the function of saving locally (requires additional parameters `-s`); Searching online for online services is much more convenient. From the perspective of saving more time, using `arya qrcode` is a better choice.

#### Save (`-s` , `--save`)

```bash
arya qrcode "https://nicelinks.site/" -s
arya qrcode "https://www.lovejade.cn/" --save
```

### ✂️ Clear the terminal screen if possible

```bash
arya clear
# Or
arya c
```

On Mac OS, if you want to implement this function, you can run the `clear` command on the terminal; but this is not particularly convenient; you can use `oh-my-zsh` to configure the command alias in the `.zshrc` file: _alias cls= 'clear'_; in this case, running `cls` is enough to clear the terminal screen content; and this is another case on Windows systems; in this case, using `arya c` is a pretty good choice.

### 📷 Greyscale: remove colour from the image.

```bash
arya img:greyscale <path>

# 👏 Or Use Alias
arya igs <path>
# local folder
arya igs ./assets/images
# local image file
arya igs ./assets/images/logo.png
# online image address
arya igs https://www.lovejade.cn/logo.png
```

All processed pictures are placed in a new folder: `arya-greyscale-imgs`. Supported Image Types: `.bmp`, `.gif`, `.jpeg`, `.jpg`, `.png`, `.tiff`.


### 🌌 Adding a shadow effect to a batch image

On Mac OS, there's a light gray outer shadow around the focal program, which gives the application a slightly three-dimensional look; the shadows fade to blend in with the final color, which also makes it look smooth and natural without being overpowering. Adding a stereoscopic outer shadow to an image in one click is a valuable tool; see the following command：

```bash
# arya img:shadow Your-Images-Dir-Path
arya img:shadow YOUR-IMGS-DIR-PATH
# Or
arya ishadow YOUR-IMGS-DIR-PATH
```

**Note**: This command is dependent on [imagemagick](https://imagemagick.org/), so you need to install it manually before using it; if you are using a Mac, you can install it in one click (for other platforms, you can download the corresponding software, see [imagemagick download](https://imagemagick.org/script/download.php)) with the following command:

```bash
brew install imagemagick
```

For the story behind the addition of this command, see the article in the article：[为文章图片添加外阴影效果](https://quickapp.lovejade.cn/how-to-add-shadow-effects-to-image/)。

### 🚝 List the script commands in package.json.

```bash
arya ls
# 👏 Or Use Alias
arya l
```

In addition, [arya jarvis](https://github.com/nicejade/arya-jarvis) is still implanting more useful features, if you have any needs, you can tell me, or expand on this basis. If you encounter any problems during use, you can always follow me feedback. Wish: Life is happy and work is well.

## Recommended links

- [清风明月轩](https://www.thebettersites.com/?ref=github.com)
- [逍遥自在轩](https://niceshare.site/?ref=github.com)
- [晚晴幽草轩](https://www.jeffjade.com/nicelinks?ref=github.com)
- [静轩之别苑](https://quickapp.lovejade.cn/?ref=github.com)
- [悠然宜想亭](https://forum.lovejade.cn//?ref=github.com)
- [静晴轩别苑](https://nice.lovejade.cn/?ref=github.com)
- [SegmentFault](https://segmentfault.com/u/jeffjade)
- [X | MarshalXuan](https://x.com/MarshalXuan)
- [Facebook](https://www.facebook.com/nice.jade.yang)

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2019-present, [nicejade](https://aboutme.lovejade.cn/?utm_source=arya.lovejade.cn).