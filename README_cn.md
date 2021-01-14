MCDReforged
--------

[English](https://github.com/Fallen-Breath/MCDReforged/blob/master/README.md)

> 这是一个基于 Python 的 Minecraft 服务端控制工具

MCDReforged（以下简称 MCDR）是一个可以在完全不对 Minecraft 服务端进行修改的情况下，通过可自定义的插件系统，提供对服务端的管理能力的工具

小至计算器、高亮玩家、b站弹幕姬，大至操控计分板、管理结构文件、自助备份回档，都可以通过 MCDR 及相配套的插件实现

非常感谢 chino_desu 以及他的 [MCDaemon 1.0](https://github.com/kafuuchino-desu/MCDaemon)

QQ群: [1101314858](https://jq.qq.com/?k=5gUuw9A)

## 优势

- 运行于服务端之上，完全不需要修改服务端，保留原汁原味的原版特性
- 可热重载的插件系统，无需重启服务端即可更新插件
- 多平台/服务端的兼容性，支持在 Linux / Windows 下运行vanilla、paper 以及 bungeecord

## 它是如何工作的？

MCDR 使用了 `Popen` 来启动服务端，以此来控制服务端的标准输入输出流。就这样

## 文档

想要了解更多关于 MCDR 的详情？去看文档吧 https://mcdreforged.readthedocs.io/ （中文版即将到来）