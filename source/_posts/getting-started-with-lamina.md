---
title: Lamina 快速入门指南
date: 2025-04-15
categories:
  - 教程
tags:
  - Lamina
  - 入门
  - 教程
---

本文将帮助你快速上手 Lamina 编程语言，从安装到编写第一个程序。

## 安装 Lamina

### Windows

从 [下载页面](/download/) 获取预编译的二进制文件，解压后即可使用。

### Linux

```bash
# 下载并解压
wget https://github.com/Lamina-dev/Lamina/releases/latest/download/lamina-linux-x64.tar.gz
tar -xzf lamina-linux-x64.tar.gz
sudo mv lamina /usr/local/bin/
```

### macOS

```bash
brew install lamina
```

## 第一个程序

创建一个名为 `hello.lm` 的文件：

```lm
print("Hello, Lamina!");
```

运行它：

```bash
lamina hello.lm
```

## 精确数学计算

Lamina 最大的特色是精确的数学计算：

```lm
// 精确分数
var fraction = 16 / 9;
print("16/9 =", fraction); // 输出: 16/9（不是 1.777...）

// 精确无理数
var root = sqrt(2);
print("√2 =", root); // 输出: √2
print("√2 × √2 =", root * root); // 输出: 2
```

## 下一步

- 阅读 [官方文档](https://wiki.lm-lang.org/) 了解更多语法特性
- 加入 [QQ群](https://qm.qq.com/cgi-bin/qm/qr?k=sSj7q14HP3UT2OlNqzmSVyp7EsPcthgZ) 与社区交流
- 在 [GitHub](https://github.com/Lamina-dev/Lamina) 查看源码
