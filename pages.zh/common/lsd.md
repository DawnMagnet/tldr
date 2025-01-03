# lsd

> 列出目录内容。
> 下一代 `ls` 命令，使用 Rust 编写。
> 更多信息：<https://github.com/Peltoche/lsd>。

- 列出文件和目录，每行一个：

`lsd -1`

- 列出当前目录中的所有文件和目录，包括隐藏的文件：

`lsd -a`

- 列出文件和目录，并在目录名称后添加斜杠 `/`：

`lsd -F`

- 以长格式列出所有文件和目录（权限、所有权、人类可读格式的大小和修改日期）：

`lsd -lha`

- 以长格式列出文件和目录，按大小排序（降序）：

`lsd -lS`

- 以长格式列出文件和目录，按修改日期排序（最旧的在前）：

`lsd -ltr`

- 仅列出目录：

`lsd -d {{*/}}`

- 以树状格式递归列出所有目录：

`lsd --tree -d`