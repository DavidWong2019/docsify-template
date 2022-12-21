# docsify模板工程

> 默认渲染Readme文件

## Docsify 使用教程

- docsify 相关网站 https://docsify.js.org/#/zh-cn/quickstart

1. 全局安装命令行工具

```shell
npm i docsify-cli -g
```

首次拉取，初始化

```shell
 docsify init

```

2. 本地预览

```shell
docsify serve ./
```

3. 部署

剔除无关文件后

```bash
-- node_modules
-- .git
```

直接把整个文件夹内容部署到nginx下
