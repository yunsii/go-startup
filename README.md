# go-startup

🚀 Golang 启动

## 做了啥？

- 配置 Go 开发环境（VS Code）
- 完成 [Go 官方入门教程](https://go.dev/doc/tutorial/getting-started)



## 国内镜像加速

[参考文章](https://learnku.com/go/wikis/38122)

```
# 类 Unix

# 启用 Go Modules 功能
go env -w GO111MODULE=on

# 配置 GOPROXY 环境变量，以下三选一

# 1. 七牛 CDN
go env -w  GOPROXY=https://goproxy.cn,direct

# 2. 阿里云
go env -w GOPROXY=https://mirrors.aliyun.com/goproxy/,direct

# 3. 官方
go env -w  GOPROXY=https://goproxy.io,direct
```

## [multi-module workspaces](https://go.dev/doc/tutorial/workspaces)

**go.work** 单仓库多模块支持

## Go 命令行工具使用

- `go mod tidy`, located and downloaded modules, and clean unused modules.
