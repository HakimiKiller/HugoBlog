---
title: "vfox"
date: "2026-02-04"
tags: ["version management","PICK"]
ShowToc: true
summary: "一个 通用 版本管理器"
---

## home

https://vfox.dev/

---

## 重要
**不要升级到v1, 因为ide无法识别**

---

## usage

```sh
# 查看所有可用的插件
vfox available

# 搜索并会自动安装插件
vfox search golang

# 查看当前已安装的所有环境和版本
vfox list
vfox c

# 切换环境 
# 作用域参数：-g -p -s
vfox use <作用域> <plugin-name>@<version>
```

---
