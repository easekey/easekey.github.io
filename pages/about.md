---
layout: page
title: About
description: 正义的程序员联盟的github之家
keywords: 正义的程序员联盟, 正义
comments: true
menu: 关于
permalink: /about/
---

我是正义的程序员联盟。

坚持就是胜利。

爱自己，爱别人，爱生活。

## 联系

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.name }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
