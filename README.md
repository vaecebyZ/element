<p align="center">
  <img src="https://cdn.rawgit.com/ElemeFE/element/dev/element_logo.svg">
</p>

<p align="center">
  <a href="https://travis-ci.org/ElemeFE/element">
    <img src="https://travis-ci.org/ElemeFE/element.svg?branch=master">
  </a>
  <a href="https://coveralls.io/github/ElemeFE/element?branch=master">
    <img src="https://coveralls.io/repos/github/ElemeFE/element/badge.svg?branch=master">
  </a>
  <a href="https://cdnjs.com/libraries/element-ui">
    <img src="https://img.shields.io/cdnjs/v/element-ui.svg">
  </a>
  <a href="https://www.npmjs.org/package/element-ui">
    <img src="https://img.shields.io/npm/v/element-ui.svg">
  </a>
  <a href="https://npmcharts.com/compare/element-ui?minimal=true">
    <img src="http://img.shields.io/npm/dm/element-ui.svg">
  </a>
  <br>
  <a href="http://img.badgesize.io/https://unpkg.com/element-ui/lib/index.js?compression=gzip&label=gzip%20size:%20JS">
    <img src="http://img.badgesize.io/https://unpkg.com/element-ui/lib/index.js?compression=gzip&label=gzip%20size:%20JS">
  </a>
  <a href="http://img.badgesize.io/https://unpkg.com/element-ui/lib/theme-chalk/index.css?compression=gzip&label=gzip%20size:%20CSS">
    <img src="http://img.badgesize.io/https://unpkg.com/element-ui/lib/theme-chalk/index.css?compression=gzip&label=gzip%20size:%20CSS">
  </a>
  <a href="#backers">
    <img src="https://opencollective.com/element/backers/badge.svg">
  </a>
  <a href="#sponsors">
    <img src="https://opencollective.com/element/sponsors/badge.svg">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg">
  </a>
</p>

> A Vue.js 2.0 UI Toolkit for Web.

自己项目需要的更改。

构建命令：从上到下。

```bash
npm run clean
npm run build:file
npm run lint
webpack --config build/webpack.conf.js
webpack --config build/webpack.common.js
webpack --config build/webpack.component.js
npm run build:utils
npm run build:umd
npm run build:theme
```

QA:

```bash
## 报错 x:\xxxx\xxxxx\element\node_modules\node-sass: Command failed. gyp verb `which` failed  python2 Error: not found: python2
## 没有安装python2依赖 [管理员权限] 安装python 2.7.x之后设置好环境变量即可
```

