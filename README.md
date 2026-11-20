# DSH 插件安装面板（已冻结）

> **这个仓库已停止更新。** 它是 `DIY-code` 里 `apps/dsh-plugin-pulse` 的旧副本，
> 继续维护会变成两份会分叉的代码，所以自本说明起冻结。

请改用下面这个地址，代码、发行版和后续更新都在那里：

- 源码：<https://github.com/YYY-DXS/DIY-code/tree/main/apps/dsh-plugin-pulse>
- 下载：<https://github.com/YYY-DXS/DIY-code/releases>（`dsh-plugin-pulse.zip`）

## 为什么冻结

同一个程序放在两个仓库里，修 bug 时只改一边，另一边就会悄悄落后。
本仓库最后一次提交停在 2026-11-14，而主仓库一直在往前走，两份代码已经不一致了。

本仓库的代码仅作历史存档保留，不再接受 issue、PR 或任何改动。

## 它原来是干什么的

给 [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) 用的可视化插件安装器：
把 [dshbase 插件目录](https://dshbase.com/plugins/directory/)里的精选做成卡片，一键安装 / 卸载，
安装前做兼容性诊断（DSH 版本、Node 版本、`peerDependencies` 范围、profile 可写性）。

功能与截图请看主仓库里的那份 README。
