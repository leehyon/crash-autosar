---
title: Introduction
type: docs
---

![](/welcome.png)

本文档将会介绍进入 AUTOSAR 领域时需要学习的基础知识、代码实践以及网络上各类资源，让对该领域感兴趣的朋友能够更快地掌握汽车软件开发的相关知识。虽然 AUTOSAR 官网提供了详尽的文档资料支持，但对于刚入行的朋友来说，英文文档浩如烟海、且晦涩难懂，另外如果仅是做应用层开发，只需对框架和相应的模块有一个大概了解即可，所以本文档尽量做到深入浅出、梳理路线，以最快时间带领大家入门和实践。

>由于本人能力有限难免有疏忽错误之处，还请不吝赐教。

[📖 在线阅读地址](https://autosar.kohsruhe.com/)

## Motivation

自己虽在汽车领域从业多年，但之前也仅了解过 AUTOSAR 的基本概念，没有具体项目的开发经验。不过目前由于工作所需，要参与一部分 AUTOSAR 应用层开发，借此文档希望从零出发、逐步积累，共同进步。

## Contributing

本文档采用 [Hugo](https://gohugo.io/) 发布。欢迎大家通过 [issue](https://github.com/leehyon/crash-autosar/issues) 提供建议，也可以通过 [pull requests](https://github.com/leehyon/crash-autosar/pulls) 来参与贡献。

安装完 `hugo` 后，可能需要先同步主题文件：

```shell
git submodule update --init --recursive
```

同步完成后，可在根目录执行以下指令来测试网站：

```shell
hugo server
```

文档在 `content/zh/docs` 目录下，修改后可以通过 pull requests 提交。