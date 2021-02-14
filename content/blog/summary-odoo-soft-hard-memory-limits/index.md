---
title: 'Odoo Soft/Hard Memory'
author: 'Lyon Liang'
description: '介绍Odoo内存相关设置'
date: '2021-02-14'
path: '/summary-odoo-soft-hard-momory'
draft: true
category: 'odoo'
tags: 
    - 'memory'
---

# 内存

对于多用户多任务操作系统而言，内存是共享资源，操作系统核心功能之一就是内存管理。

- Soft memory limit: 任务能够使用的最大虚拟内存数量
- Hard memory limit: Soft memory的上限

# ulimit

在Linux操作系统上，可以通过命令`ulimit`来查看设置内存相关参数。

查看Soft Memory Limit:

```bash
ulimit -Sn
```

查看Hard Memory Limit:

```bash
ulimit -Hn
```

# Odoo

--limit-memory-soft <limit>
Maximum allowed virtual memory per worker. If the limit is exceeded, the worker is killed and recycled at the end of the current request.

Defaults to 2048MB.

--limit-memory-hard <limit>
Hard limit on virtual memory, any worker exceeding the limit will be immediately killed without waiting for the end of the current request processing.

soft和hard的区别在于，一旦达到hard对应的数量，worker进程将会被立即杀掉。

# 参考

1. https://www.geeksforgeeks.org/ulimit-soft-limits-and-hard-limits-in-linux/
2. https://www.odoo.com/zh_CN/forum/help-1/different-between-limit-memory-hard-and-limit-memory-soft-139661