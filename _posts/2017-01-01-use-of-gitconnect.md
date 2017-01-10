---
layout: post
title:  "use of gitconnect"
date:   2017-01-01 18:34:10 +0700
categories: [DNS, lsy]
---

#github解析域名

----------
##1.向Github Pages仓库中添加一个CNAME文件
###其中只能包含一个顶级域名
    example.com
##2.向DNS配置中添加3条记录
| ------------- |:-------------:| -----:|
| @ | A | 192.30.252.153 |
| @ | A | 192.30.252.154 |
| www | CNAME | username.github.io. | 




