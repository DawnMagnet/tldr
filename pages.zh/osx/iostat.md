# iostat

> 报告设备统计信息。
> 更多信息：<https://ss64.com/mac/iostat.html>。

- 显示快照设备统计信息（每次传输的千字节数、每秒传输次数、每秒兆字节数）、CPU统计信息（用户模式、系统模式和空闲模式下的时间百分比）和系统负载平均值（过去1分钟、5分钟和15分钟）：

`iostat`

- 仅显示设备统计信息：

`iostat -d`

- 每2秒显示CPU和磁盘统计信息的增量报告：

`iostat 2`

- 每秒显示第一个磁盘的统计信息，直到手动停止：

`iostat -w 1 disk0`

- 每3秒显示第二个磁盘的统计信息，10次：

`iostat -w 3 -c 10 disk1`

- 使用旧式 `iostat` 显示格式。显示每秒传输的扇区数、每秒传输次数、每笔交易的平均毫秒数，以及来自默认样式显示的CPU统计信息和负载平均值：

`iostat -o`

- 显示总设备统计信息（KB/t：每次传输的千字节数，如前所述，xfrs：传输总次数，MB：传输的总兆字节数）：

`iostat -I`