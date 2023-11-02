---
title: Gradient descent(梯度下降）
date: 2023-06-24 16:19:49
tags:
mathjax: true
---
### 特性（property）

两次梯度下降结果可能完全不同

## algorithm

$j(w,b)=\frac{1}{2m} \displaystyle \sum_{i=1}^m(f_{w,b}(x^{(i)})-y^{(i)})^2$

$w=w - \alpha \frac{\partial}{\partial w}J(w,b)$,其中 $\alpha$代表学习率。
$b=b - \alpha \frac{\partial}{\partial w}J(w,b)$,需要注意,w,b要同时更新(simultaneously)，通过中间变量实现。

$temp_w=w - \alpha \frac{\partial}{\partial w}J(w,b)$
$temp_b=b - \alpha \frac{\partial}{\partial w}J(w,b)$
