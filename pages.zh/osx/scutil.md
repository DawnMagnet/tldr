# scutil

> 管理系统配置参数。
> 设置配置时需要root权限。
> 更多信息：<https://keith.github.io/xcode-man-pages/scutil.8.html>。

- 显示DNS配置：

`scutil --dns`

- 显示代理配置：

`scutil --proxy`

- 获取计算机名称：

`scutil --get ComputerName`

- 设置计算机名称：

`sudo scutil --set ComputerName {{computer_name}}`

- 获取主机名：

`scutil --get HostName`

- 设置主机名：

`scutil --set HostName {{hostname}}`