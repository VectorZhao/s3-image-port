# 自部署指南 (WIP)

[[toc]]

## 静态部署

由于是静态网站，所以只要将生成的文件部署到任何支持静态文件的服务器上即可，
无论是放到 GitHub Pages，还是放到自己的服务器上。

## 服务器渲染部署

::: info
需要 node.js 环境。在 20.x 版本下测试通过，较早的版本应该也没问题。
:::

## Docker 部署

与[服务器渲染部署](#服务器渲染部署)类似，Docker 部署只是将服务端渲染的应用打包成 Docker 镜像，方便机器上没有 Node.js 环境的情况下部署。
