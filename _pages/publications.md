---
title: "发表成果 | 张圆教授课题组 | 沈阳建筑大学"
layout: gridlay
excerpt: "发表成果 | 张圆教授课题组 | 沈阳建筑大学"
sitemap: false
permalink: /publications/
---

# 文章列表

{% for publi in site.data.publist %}

{{ publi.title }} <br />
<em><strong>{{ publi.journal }}</strong></em>, {{ publi.year }} <br />
{{ publi.authors }} <br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}
