# go-startup

ð Golang å¯å¨

## åäºå¥ï¼

- éç½® Go å¼åç¯å¢ï¼VS Codeï¼
- å®æ [Go å®æ¹å¥é¨æç¨](https://go.dev/doc/tutorial/getting-started)



## å½åéåå é

[åèæç« ](https://learnku.com/go/wikis/38122)

```
# ç±» Unix

# å¯ç¨ Go Modules åè½
go env -w GO111MODULE=on

# éç½® GOPROXY ç¯å¢åéï¼ä»¥ä¸ä¸éä¸

# 1. ä¸ç CDN
go env -w  GOPROXY=https://goproxy.cn,direct

# 2. é¿éäº
go env -w GOPROXY=https://mirrors.aliyun.com/goproxy/,direct

# 3. å®æ¹
go env -w  GOPROXY=https://goproxy.io,direct
```

## [multi-module workspaces](https://go.dev/doc/tutorial/workspaces)

**go.work** åä»åºå¤æ¨¡åæ¯æ

## Go å½ä»¤è¡å·¥å·ä½¿ç¨

- `go mod tidy`, located and downloaded modules, and clean unused modules.
