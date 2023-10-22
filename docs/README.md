# 使用docsify初始化和发布Github Pages

> [docsify文档](https://docsify.js.org/#/zh-cn/)

## [快速开始](https://docsify.js.org/#/zh-cn/quickstart?id=%e5%bf%ab%e9%80%9f%e5%bc%80%e5%a7%8b)

推荐全局安装 `docsify-cli` 工具，可以方便地创建及在本地预览生成的文档。

```
npm i docsify-cli -g
```

## [初始化项目](https://docsify.js.org/#/zh-cn/quickstart?id=%e5%88%9d%e5%a7%8b%e5%8c%96%e9%a1%b9%e7%9b%ae)

如果想在项目的 `./docs` 目录里写文档，直接通过 `init` 初始化项目。

```
docsify init ./docs
```

## [开始写文档](https://docsify.js.org/#/zh-cn/quickstart?id=%e5%bc%80%e5%a7%8b%e5%86%99%e6%96%87%e6%a1%a3)

初始化成功后，可以看到 `./docs` 目录下创建的几个文件

* `index.html` 入口文件
* `README.md` 会做为主页内容渲染
* `.nojekyll` 用于阻止 GitHub Pages 忽略掉下划线开头的文件

直接编辑 `docs/README.md` 就能更新文档内容，当然也可以[添加更多页面](https://docsify.js.org/#/zh-cn/more-pages)。

## [本地预览](https://docsify.js.org/#/zh-cn/quickstart?id=%e6%9c%ac%e5%9c%b0%e9%a2%84%e8%a7%88)

通过运行 `docsify serve` 启动一个本地服务器，可以方便地实时预览效果。默认访问地址 [http://localhost:3000](http://localhost:3000/) 。

```
docsify serve docs
```

## [部署GitHub Pages](https://docsify.js.org/#/zh-cn/deploy?id=github-pages)

GitHub Pages 支持从三个地方读取文件

* `docs/` 目录
* master 分支
* gh-pages 分支

我们推荐直接将文档放在 `docs/` 目录下，在设置页面开启 **GitHub Pages** 功能并选择 `master branch /docs folder` 选项。
