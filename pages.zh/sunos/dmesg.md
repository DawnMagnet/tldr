# dmesg

> 将内核消息写入 `stdout`。
> 更多信息：<https://www.unix.com/man-page/sunos/1m/dmesg>。

- 显示内核消息：

`dmesg`

- 显示此系统上可用的物理内存：

`dmesg | grep -i memory`

- 每次显示一页内核消息：

`dmesg | less`