---
layout: post
title: diff 和 patch
categories: unix-like
tag:
    - diff
    - patch
    - unix
---


### Diff
```
$ diff -rNu dir1 dir2
// 使用 dir2 对 dir1 进行打补丁
// -r 递归，  -u 统一格式，  -N 正确处理删除和创建的文件
```



### Patch
```
$ patch -p0 < file.diff             // -p0 不忽略目录
```
