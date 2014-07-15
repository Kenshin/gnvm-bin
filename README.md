GNVM: Node.js version manager on Windows by GO
================================
`GNVM` is simple multi node.js version manager on Windows by GO, this is only `GNVM` binary repo.

Documentation
---
[中文版](https://github.com/kenshin/gnvm/blob/master/README_CN.md) | [English](https://github.com/kenshin/gnvm/blob/master/README.md)

CHANGELOG
---
* **2014-07-15, Version `0.1.2`:**
    * Adapter go version 1.3.
    * Fix bug of usage `gnvm update latest -g` adapter go version error.

* **2014-06-06, Version `0.1.1`:**
    * Change `util/p/print.go` to `github.com/Kenshin/cprint`.
    * change `util/curl/curl.go` to `github.com/Kenshin/curl`.
    * Add this project to travis-ci.org.
    * Remove `nodehandle.cmd` method.
    * Optimize `nodehandle.copy` method logic.
    * Fix bug of When not global node.exe, need get gnvm.exe path.

* **2014-05-30, Version `0.1.0`:**
    * version
    * install
    * uninstall
    * use
    * update
    * ls
    * node-version
    * config

LICENSE
---
(The MIT License)

Copyright (c) 2014 Kenshin Wang <kenshin@ksria.com>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
