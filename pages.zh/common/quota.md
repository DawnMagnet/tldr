# 配额

> 显示用户的磁盘空间使用情况和分配的限制。
> 更多信息：<https://manned.org/quota>。

- 以人类可读的单位显示当前用户的磁盘配额：

`quota -s`

- 详细输出（还显示未分配存储的文件系统配额）：

`quota -v`

- 安静输出（仅显示使用超出配额的文件系统配额）：

`quota -q`

- 打印当前用户所属于组的配额：

`quota -g`

- 显示另一个用户的磁盘配额：

`sudo quota -u {{用户名}}`