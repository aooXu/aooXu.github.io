---
layout: post
title: 计算机安全-Linux文件权限 (ls -l输出的结果)
description: 今天看到Linux的权限模型中每个文件的权限是一个10位String, 所以有些不明所以.
---

# DAC

DAC指自决定权限控制(Discretionary Access Control), 是一种访问控制模式(Access Control Pattern). 在这种模式中系统的权限不由系统决定而是由创建者自己决定. Linux文件系统就采取了这种访问控制pattern

# ls -l 

ls -l 输出的结果是一个10位的String, 这个字符串的第一位是分隔符'-', 没有实际含义, 第2-4位表示创建者的权限, 第5-7位表示和创建者同一用户组的用户的权限, 第8-10位表示其他用户的权限. 

# 例子

例如如果输出的结果是`-rwxr-x---` 
* 第一个`-`没有实际含义
* 第2-4位`rwx`表示创建者的权限包括`r`ead, `w`rite 和e`x`ecute
* 第5-7位`r-x`表示创造者所处的用户组的权限是`r`ead, 和e`x`ecute
* 最后三位`---`表示其他人没有权限

# Chmod指令中的数字

例如`chmod file 775`因为存在三种可能的操作, `read`, `write`和`execute`所以我们可以用三位二进制数字表示给予哪几种权限, 所以十进制的**7**就是二进制的**111**, 十进制的**5**就是二进制的**101**