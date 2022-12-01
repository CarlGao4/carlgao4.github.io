---
layout: cimover
title: "ClassIn Mover"
nofooter: true
---

# [![ClassIn-Mover icon 32x32](../ClassIn_Mover_32.png) ClassIn Mover ![GitHub all releases](https://img.shields.io/github/downloads/CarlGao4/ClassIn-Mover/total?label=%E4%B8%8B%E8%BD%BD%E9%87%8F)](https://carlgao4.github.io/ClassIn-Mover/) 

[English](..)

用于移动 `ClassIn` 教室窗口以退出专注学习模式的小程序。

支持的 `ClassIn` 版本：`3.0.2.130` ~ `3.0.5.1`, `3.0.7.x`, `4.x`。（早于 `3.0.2.130` 的版本没有专注学习模式）

请注意，本项目的目的是为了帮助因专注学习模式无法截屏、查找资料等原因造成学习受到影响的同学，而不是满足某些同学不想学习的愿望。

在将来的更新过程中，此程序可能会失效。

## 下载地址

#### ![GitHub release (latest by date)](https://img.shields.io/github/v/release/CarlGao4/ClassIn-Mover?label=%E6%AD%A3%E5%BC%8F%E7%89%88)

#### [Download latest version from Github Release (github.com)](../download_github.html) {#dl_gh}

#### [Download latest version from Gitee mirror (gitee.com)](../download_gitee.html) {#dl_gt}

## 组件

### ClassIn Mover Classic

除了这一版采用了Tk的GUI，操作方式与v1.0.0没有区别。

#### 使用方法

在正常进入教室前，请运行本程序。

此后，程序将自动检测ClassIn教室窗口，并阻止它占用整个屏幕。

正常运行时，程序会每秒钟输出一次运行状态。

### ClassIn Mover

进入ClassIn教室之前，运行ClassIn Mover，在屏幕左上方会出现一个半透明的ClassIn Mover图标。左键单击可以打开主菜单，可以在这里选择一个ClassIn窗口，并对其最大化、最小化、置顶、取消置顶。

默认情况下，自动处理窗口处于开启状态，当检测到新ClassIn窗口时会自动尝试将其退出专注学习模式。可以右键点击悬浮球关闭这一特性。注意，主菜单上的自动处理按钮只会对选中的窗口处理，而不会打开这一功能。

## 已知问题

-   **该程序调用Windows的本地API，因此只能在Windows上运行。**

## 反馈

你可以在 [GitHub issues](https://github.com/CarlGao4/ClassIn-Mover/issues) 上反馈问题或者提交需求。Gitee issues已经被关闭。注意，在提问及交流时请使用英语，因为我们尊重广大开源社区。

## [版本历史记录](../releases/zh-cn)