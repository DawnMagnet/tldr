# 唤醒局域网

> 发送数据包以唤醒启用唤醒局域网（WOL）的计算机。
> 更多信息：<https://github.com/jpoliv/wakeonlan>。

- 通过指定 MAC 地址向本地网络上的所有设备发送数据包（255.255.255.255）：

`wakeonlan {{01:02:03:04:05:06}}`

- 通过 IP 地址向特定设备发送数据包：

`wakeonlan {{01:02:03:04:05:06}} -i {{192.168.178.2}}`

- 打印命令，但不执行它们（干运行）：

`wakeonlan -n {{01:02:03:04:05:06}}`

- 以安静模式运行：

`wakeonlan -q {{01:02:03:04:05:06}}`