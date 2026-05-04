---
title: Lamina v0.3 发布 - 新增向量运算与符号计算增强
date: 2025-04-28
categories:
  - 发布
tags:
  - Lamina
  - 新版本
  - 向量运算
---

Lamina v0.3 版本正式发布！本次更新带来了多项重要改进，包括向量运算支持、符号计算增强以及性能优化。

## 主要更新

### 向量运算

现在 Lamina 原生支持向量运算，可以直接对向量进行加法、点积等操作：

```lm
var v1 = [1, 2, 3];
var v2 = [4, 5, 6];
print("v1 + v2 =", v1 + v2);
print("v1 · v2 =", dot(v1, v2));
```

### 符号计算增强

改进了无理数的精确表示和运算，确保计算结果的数学正确性：

```lm
var root = sqrt(2);
print("√2 × √2 =", root * root); // 输出: 2（精确结果）
```

### 性能优化

- LMVM 虚拟机执行效率提升约 15%
- 内存占用减少约 10%
- 启动速度优化

## 获取更新

前往 [下载页面](/download/) 获取最新版本，或通过源码构建体验最新功能。

欢迎在 [GitHub](https://github.com/Lamina-dev/Lamina) 提交 Issue 和 PR，共同完善 Lamina！
