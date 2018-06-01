---
layout: page
title: About
description: 为宅而生靠番过活
keywords: Koryelu, Keyi Lu
comments: true
menu: 关于
permalink: /about/
---

我是Koryelu，为宅而生，靠番过活。

喜欢「善良的软萌妹」。

坚信肥宅有power，有爱世界不孤单。

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
