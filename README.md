![logo](http://i.imgur.com/Z4iPSgQ.png) GNVM - Node.js 多版本管理器  
================================  
[![Version][version-badge]][version-link]
#### `GNVM` 是一个简单的 `Windows` 下 Node.js 多版本管理器，类似的 `nvm` `nvmw` `nodist` 。  
```
c:\> gnvm install latest 1.0.0-x86 1.0.0-x64 5.0.0
Start download Node.js versions [5.10.1, 1.0.0, 1.0.0-x86, 5.0.0].
5.10.1: 18% [=========>__________________________________________] 4s
 1.0.0: 80% [==========================================>_________] 40s
1.0...: 50% [==========================>_________________________] 30s
 5.0.1: 100% [==================================================>] 20s
End download.

c:\> gnvm ls
5.1.1 -- latest
1.0.0
1.0.0 -- x86
5.0.0 -- global

c:\> gnvm use latest
Set success, current Node.js version is 5.10.0.

c:\> gnvm update latest
Update success, current Node.js latest version is 5.10.0.
```

特色
---
* 单文件，不依赖于任何环境。
* 下载即用，无需配置。
* 彩色日志输出。
* 支持多线程下载。
* 内置 [TAOBAO](http://npm.taobao.org/mirrors/node)，方便切换，也支持自定义。
* 支持 `NPM` 下载/安装/配置。

主页
---
[![Website][www-badge]][www-link]

文档
---
[English](https://github.com/kenshin/gnvm/blob/master/README.en.md) | [繁體中文](https://github.com/kenshin/gnvm/blob/master/README.tw.md)

许可
---
[![license-badge]][license-link]

<!-- Link -->
[www-badge]:        https://img.shields.io/badge/website-gnvm.ksria.com-1DBA90.svg
[www-link]:         http://ksria.com/gnvm
[version-badge]:    https://img.shields.io/badge/lastest_version-0.2.0-blue.svg
[version-link]:     https://github.com/kenshin/gnvm/releases
[license-badge]:    https://img.shields.io/github/license/mashape/apistatus.svg
[license-link]:     https://opensource.org/licenses/MIT
