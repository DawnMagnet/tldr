# 算术

> 简单算术问题的测验。
> 更多信息：<https://manned.org/arithmetic.6>。

- 开始一个算术测验：

`arithmetic`

- 指定一个或多个算术 [运]算符号以获取相应的问题：

`arithmetic -o {{+|-|x|/}}`

- 指定一个范围。加法和乘法问题的数字将在 0 到范围之间（包括范围）。减法和除法问题将要求结果和要操作的数字在 0 到范围之间：

`arithmetic -r {{7}}`