# Batter_Regex
关于本项目详细介绍和例子请阅读：[实现 一个满足你特殊癖好的 正则](http://blog.csdn.net/dalerkd/article/details/71257696)

在线地址请访问:[https://dalerkd.github.io/Batter_Regex/Better_Regex.html](https://dalerkd.github.io/Batter_Regex/Better_Regex.html)
## 目的

实现一个更实用的正则工具，包括**分别匹配并合并两块数据**的能力。
此外它将提供更多的运行时信息给用户，包括匹配时第几次的信息。
匹配时计算是一个很好的方向。即我们可以对每次匹配到字符串做更多处理，而在其中添加1，2，3等次序信息是一个初步的主意。

## 例子：

新的操作符```&t```来替换为运行时的次数信息。
eg:
```
a
b
c
```
使用：
```
\w
```
匹配成
```
&t$0
```
点击**匹配**结果是：
```
1a
2b
3c
```

## 操作符```&```可以被修改
