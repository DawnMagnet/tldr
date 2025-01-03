# aura

> Aura 包管理器：一个安全的多语言包管理器，适用于 Arch Linux 和 AUR。
> 更多信息：<https://github.com/fosskers/aura>。

- 从官方仓库和 AUR 中搜索包：

`aura --aursync --both --search {{关键字|正则表达式}}`

- 从 AUR 安装一个包：

`aura --aursync {{包名}}`

- 以详细模式更新所有 AUR 包，并删除所有构建依赖：

`aura --aursync --diff --sysupgrade --delmakedeps --unsuppress`

- 从官方仓库安装一个包：

`aura --sync {{包名}}`

- 同步并更新所有来自官方仓库的包：

`aura --sync --refresh --sysupgrade`

- 使用包缓存降级一个包：

`aura --downgrade {{包名}}`

- 移除一个包及其依赖：

`aura --remove --recursive --unneeded {{包名}}`

- 移除孤立包（作为依赖安装但不被任何包需要的包）：

`aura --orphans --abandon`