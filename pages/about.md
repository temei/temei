---
layout: page
title: About me
description: 人生嗷嗷待哺
keywords: 特眉, 得施邦, temei
comments: true
menu: 关于我
permalink: /about/
---

我是特眉，我也是得施邦。


 __                                     
/\ \__                            __    
\ \ ,_\    __    ___ ___      __ /\_\   
 \ \ \/  /'__`\/' __` __`\  /'__`\/\ \  
  \ \ \_/\  __//\ \/\ \/\ \/\  __/\ \ \ 
   \ \__\ \____\ \_\ \_\ \_\ \____\\ \_\
    \/__/\/____/\/_/\/_/\/_/\/____/ \/_/
                                        
                                        

## 联系我

{% for website in site.data.social %}
* {{ 新浪微博 }}：[@{{ 得施邦 }}]({{ https://weibo.com/flora6 }})

* {{ 电子邮箱 }}：temei4fun@outlook.com,florar43@qq.com

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
