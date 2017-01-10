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

<style> 
.table-c table{border-right:1px solid #000;border-bottom:1px solid #000} 
.table-c table td{border-left:1px solid #000;border-top:1px solid #000} 
/* 
css 注释： 
只对table td设置左与上边框； 
对table设置右与下边框； 
为了便于截图，我们将css 注释说明换行排版 
*/ 
</style> 
<div class="table-c"> 
<table width="400" border="0" cellspacing="0" cellpadding="0"> 
<tr> 
<td width="105">@</td> 
<td width="181">A</td> 
<td width="112">192.30.252.153</td> 
</tr> 
<tr> 
<td>@</td> 
<td>A</td> 
<td>192.30.252.153</td> 
</tr> 
<tr> 
<td>www</td> 
<td>CNAME</td> 
<td>username.github.io</td> 
</table> 
