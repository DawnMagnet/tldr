# go env

> 管理 Go 工具链使用的环境变量。
> 更多信息：<https://golang.org/cmd/go/#hdr-Print_Go_environment_information>。

- 显示所有环境变量：

`go env`

- 显示特定环境变量：

`go env {{GOPATH}}`

- 将环境变量设置为某个值：

`go env -w {{GOBIN}}={{path/to/directory}}`

- 重置环境变量的值：

`go env -u {{GOBIN}}`