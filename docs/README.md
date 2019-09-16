## Goal and Philosophy

The ideal goal is to help us deal with things that can be more precise in the simplest way. `Arya Jarvis` is an attempt to do this, it designed to save developers more time and energy.

## Prerequisites

[Node.js](https://nodejs.org/en/) (>= 8.\*), Npm version 5+ ([Yarn](https://www.jeffjade.com/2017/12/30/135-npm-vs-yarn-detial-memo/) preferred).

## Install

```bash
npm i arya-jarvis -g
# Or
yarn add global arya-jarvis
```

## Usage

The following two functions can support multiple format files, such as: `.js`, `.vue`, `.ux`, `.less`, `.scss`, `.css`, `.json`, `.md`, `.html`, `.qxml`, `.wxml`.

#### 💄 Prettier the code under the specified path.

```bash
arya prettier index.js
# 👏 Or Use Alias
arya p ./src/**/**/*.js
# 👍🙌 Or Use Alias & Wildcard
arya p .
```

#### 🔬 Listen for code changes in the specified path and prettier them.

```bash
arya watcher index.js
# 👏 Or Use Alias
arya w ./src/**/**/*.js
# 👍🙌 Or Use Alias & Wildcard
arya w .
```

It is worth mentioning that the code formatting of this project is handled by `arya w .`. Thanks to myself for developing this `arya jarvis` in my spare time, **I am super like it**.

#### 🌍 Used to quickly build a local web server.

```bash
arya server
# 👏 Or Use Alias
arya s
```

#### ⚡️ Find your local IP address and print it.

```bash
arya ip
```

#### 👀 View programs that occupy the specified port.

```bash
arya port 8080
```

#### 🚝 List the script commands in package.json.

```bash
arya ls
# 👏 Or Use Alias
arya l
```

In addition, [arya jarvis](https://github.com/nicejade/arya-jarvis) is still implanting more useful features, if you have any needs, you can tell me, or expand on this basis. If you encounter any problems during use, you can always follow me feedback. Wish: Life is happy and work is well.

## Recommended links

- [**NICE LINKS**](https://nicelinks.site/?utm_source=github.com)
- [About Me](https://about.me/nicejade/?utm_source=github.com)
- [**Hexo Blog**](https://jeffjade.com/?utm_source=github.com)
- [VuePress Blog](https://www.lovejade.cn/?utm_source=github.com)
- [VuePress Blog](https://nice.lovejade.cn/?utm_source=github.com)
- [Ghost Blog](https://quickapp.lovejade.cn/?utm_source=github.com)
- [Jekyll blog](https://blog.lovejade.cn/?utm_source=github.com)
- [SegmentFault](https://segmentfault.com/u/jeffjade)
- [Wei bo](http://weibo.com/jeffjade/)
- [Zhi Hu](https://www.zhihu.com/people/yang-qiong-pu/)
- [Jian Shu](http://www.jianshu.com/u/9aae3d8f4c3d)
- [Twitter](https://twitter.com/nicejadeyang)
- [Facebook](https://www.facebook.com/nice.jade.yang)

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2019-present, [nicejade](https://aboutme.lovejade.cn/?utm_source=arya-jarvis).