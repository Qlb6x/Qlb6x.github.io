---
layout: post
title:  "GithubPages绑定域名"
date:   2017-01-01 14:25:20 +0700
categories: [git]
---

1.	向Github Pages仓库中添加一个CNAME文件
其中只能包含一个顶级域名

```
example.com
```

2.	向DNS配置中添加3条记录
<table style="border:1px solid #000"><tr><td>
@
</td><td>
A
</td><td>
192.30.252.153
</td></tr><tr><td>
@
</td><td>
A
</td><td>
192.30.252.154
</td></tr><tr><td>
www
</td><td>
CNAME
</td><td>
username.github.io
</td></tr></table>


