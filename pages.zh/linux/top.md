# top

> 显示正在运行的进程的动态实时信息。
> 更多信息：<https://manned.org/top>。

- 启动 `top`：

`top`

- 不显示任何闲置或僵尸进程：

`top -i`

- 仅显示由给定用户拥有的进程：

`top -u {{用户名}}`

- 按字段对进程进行排序：

`top -o {{字段名称}}`

- 显示给定进程的单独线程：

`top -Hp {{进程ID}}`

- 仅显示具有给定 PID（以逗号分隔的列表传递的进程）。 (通常你不会知道 PID，这个例子从进程名称中获取 PID)：

`top -p $(pgrep -d ',' {{进程名称}})`

- 显示关于交互命令的帮助：

`?`