---
layout: post
title: "JRebel 激活方式二备份"
date: 2026-01-15 14:00:00 +0800
categories: 技术
tags: jrebel 激活 备份
---

# JRebel 激活方式二备份

## 方式二（推荐）

### 准备反向代理服务包

访问最新 Github 地址（https://github.com/yu-xiaoyao/jrebel-license-active-server/releases/tag/v-20251111）选择对应的版本下载。

双击运行下载的 exe 文件，出现命令框（不要关闭！）

注意：在操作完成之前命令框不能关闭，否则无法成功。

### 激活步骤

1. 打开 IDEA 选择 help-jrebel-activation
2. 选择 Connect to License Server
3. 输入对应的激活信息

### 最后一步、离线使用

JRebel 激活之后默认是联网使用的，在该模式下，JRebel 会一直联网监测激活信息；所以需要将 JRebel 调为离线使用：

1. 直接点击 Work offline 按钮即可

## 注意事项

- 命令框在操作完成之前不能关闭
- 建议使用离线模式，避免联网监测激活信息
- 请确保下载的是最新版本的反向代理服务包