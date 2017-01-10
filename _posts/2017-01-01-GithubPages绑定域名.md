---
layout: post
title:  "GithubPages绑定域名"
date:   2017-01-01 14:25:20 +0700
categories: [git]
---

### 1. 向Github Pages仓库中添加一个CNAME文件
其中只能包含一个顶级域名

```
example.com
```

### 2. 向DNS配置中添加3条记录
<style> 
table{border-right:1px solid #000;border-bottom:1px solid #000} 
table td{border-left:1px solid #000;border-top:1px solid #000;padding:0px 0px 0px 10px} 
</style>  
<table width="400" border="0" cellspacing="0" cellpadding="0"> 
<tr> 
<td width="80">A</td> 
<td width="80">@</td> 
<td width="80">192.30.252.153</td> 
</tr> 
<tr> 
<td>A</td> 
<td>@</td> 
<td>192.30.252.154</td> 
</tr> 
<tr> 
<td>CNAME</td> 
<td>www</td> 
<td>username.github.io</td> 

