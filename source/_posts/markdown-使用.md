title: markdown-使用
date: 2023-06-23 12:10:43
tags:
-----

//>引用

> 引用

# 有序列表

a：

1. aa
2. bb
3. cc

# 无序列表

- a
- b
- c

* d
  #任务列表
  abc:

- [ ]  a
- [ ]  b
- [ ]  c

# 代码块

#### ```java

```java
Public static void main(String [] args){
  System.out.println("hello!");
}
```

# 数学公式

$a$

$$
\frac{\partial f}{\partial x}=2\sqrt{a}x

$$

# 表格：


| a                     | b | c |
| :---------------------- | :-: | --: |
| /左对齐，居中，右对齐 |  |   |

# 脚注：

aaa[^ke]

# 横线

---

---

# 行内元素

## 链接

[bilibili](bilibili.com"我的大学”)

[bilibili][id]
[id]: bilibili.com"university"

请参考[有序列表](#有序列表)

*斜体*
**加粗**
`print()`/行内代码
<u>下划线</u>

:smile: /国际通用表情代码😕
:smile:

[^ke]: 123456
