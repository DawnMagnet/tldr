# 日历

> 显示一个突出显示当前日期的日历。
> 更多信息：<https://man.freebsd.org/cgi/man.cgi?cal>。

- 显示当前月份的日历：

`cal`

- 显示特定年份的日历：

`cal {{year}}`

- 显示特定月份和年份的日历：

`cal {{month}} {{year}}`

- 显示当前年份的完整日历：

`cal -y`

- 不要突出显示今天，并显示跨越日期的3个月：

`cal -h -3 {{month}} {{year}}`

- 显示当前年份中特定月份之前的2个月和之后的3个月：

`cal -A 3 -B 2 {{month}}`

- 显示儒略日（从1开始，从1月1日起编号）：

`cal -j`