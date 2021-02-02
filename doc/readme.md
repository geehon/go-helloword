# Hello Go (Learn golang)

## 安装Golang

官方最新版安装教程 [Link](https://golang.org/doc/install?download=go1.15.7.linux-amd64.tar.gz)

## 设置 Go modules 镜像代理服务

goproxy.io 是全球最早的 Go modules 镜像代理服务之一, 采用 CDN 加速服务为开发者提供依赖下载, 该服务由一批热爱开源, 热爱 Go 语言的年轻人开发维护。从 Go 1.11 开始 Go 语言开始支持 Go modules 来解决大家长久以来诟病的依赖管理问题，目前 Go modules 功能已经符合生产环境标准。

> [GOPROXY.IO快速上手](https://goproxy.io/zh/docs/getting-started.html)

### 开启 Go module 功能

Mac/Linux

```shell
export GO111MODULE="on"
```

Windows

```powershell
$env:GO111MODULE="on"
```

### 配置 Goproxy 环境变量

```shell
go env -w GOPROXY="https://goproxy.io,direct"
```

## vscode扩展安装

golang 官方扩展 [golang.go](https://marketplace.visualstudio.com/items?itemName=golang.go)

推荐安装 [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
