---
presentation:
  theme: solarized.css
  mouseWheel: true
  width: 1000
  height: 900
  slideNumber: true
  progress: true
  minScale: 0.2
  maxScale: 1.5
---

<!-- slide -->
# HTTP培训

<!-- slide -->
# 目标

- 目的：规范RESTful接口
- 重点
  - URL语法
  - 报文结构
    - Method方法
    - Status Code状态码
    - 请求头部

<!-- slide -->
# 谈谈你们知道的HTTP

## 轮流坐庄


<!-- slide -->

![2021-02-22-20-33-03](http://markdown.docs.lyon.pub/2021-02-22-20-33-03.png)

<!-- slide -->

# URL - 资源

![2021-02-22-20-35-16](http://markdown.docs.lyon.pub/2021-02-22-20-35-16.png)

<!-- slide -->

# URL - 例子

![2021-02-22-20-36-56](http://markdown.docs.lyon.pub/2021-02-22-20-36-56.png)

## 它们有什么共同特征？

<!-- slide -->

# URL 

![2021-02-22-20-38-42](http://markdown.docs.lyon.pub/2021-02-22-20-38-42.png)

<!-- slide -->

# URL语法

![2021-02-22-20-39-28](http://markdown.docs.lyon.pub/2021-02-22-20-39-28.png)

<!-- slide -->

# URL练习

![2021-02-22-20-39-28](http://markdown.docs.lyon.pub/2021-02-22-20-39-28.png)

![2021-02-22-20-45-19](http://markdown.docs.lyon.pub/2021-02-22-20-45-19.png)

![2021-02-22-20-45-39](http://markdown.docs.lyon.pub/2021-02-22-20-45-39.png)

http://47.96.20.37:18891/#/bim/info

<!-- slide -->

# HTTP报文结构

- 起始行 (Start line)
- 头部 (Header)
- 主体 (Body)

![2021-02-22-20-53-33](http://markdown.docs.lyon.pub/2021-02-22-20-53-33.png)

<!-- slide -->

# HTTP请求

![2021-02-22-20-55-39](http://markdown.docs.lyon.pub/2021-02-22-20-55-39.png)

起始行
- 方法
- URL
- 协议

<!-- slide -->

# HTTP响应

![2021-02-22-20-55-39](http://markdown.docs.lyon.pub/2021-02-22-20-55-39.png)

起始行
- 协议
- 状态码
- 原因描述

<!-- slide -->

# HTTP方法 - GET

![2021-02-22-20-57-59](http://markdown.docs.lyon.pub/2021-02-22-20-57-59.png)

<!-- slide -->

# HTTP方法 - HEAD

![2021-02-22-20-58-43](http://markdown.docs.lyon.pub/2021-02-22-20-58-43.png)

<!-- slide -->

# HTTP方法 - PUT

![2021-02-22-20-59-11](http://markdown.docs.lyon.pub/2021-02-22-20-59-11.png)

<!-- slide -->

# HTTP方法 - POST

![2021-02-22-21-00-08](http://markdown.docs.lyon.pub/2021-02-22-21-00-08.png)

<!-- slide -->

# HTTP方法 - DELETE

![2021-02-22-21-34-10](http://markdown.docs.lyon.pub/2021-02-22-21-34-10.png)

<!-- slide -->

# HTTP方法 - OPTIONS

![2021-02-22-21-33-49](http://markdown.docs.lyon.pub/2021-02-22-21-33-49.png)

<!-- slide -->

# HTTP状态码

![2021-02-22-21-40-41](http://markdown.docs.lyon.pub/2021-02-22-21-40-41.png)

<!-- slide -->

# 常用HTTP状态码

![2021-02-22-21-42-43](http://markdown.docs.lyon.pub/2021-02-22-21-42-43.png)

<!-- slide -->

# 常用HTTP状态码

![2021-02-22-21-43-04](http://markdown.docs.lyon.pub/2021-02-22-21-43-04.png)

<!-- slide -->

# 常用HTTP状态码

![2021-02-22-21-43-25](http://markdown.docs.lyon.pub/2021-02-22-21-43-25.png)

<!-- slide -->

# Recap

1. 我们如何找到资源？
2. 我们如何对资源进行操作？
3. 我们如何知道操作结果？


<!-- slide -->

参考：
1. 《HTTP权威指南》
2. https://github.com/woai30231/http