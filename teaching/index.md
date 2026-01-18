---
layout: single
title: "Lecturing"
permalink: /teaching/
---

{% for c in site.data.teaching %}
### {{ c.title }}

{{ c.meta }}

{{ c.description }}

{% if c.links and c.links.size > 0 %}
{% for l in c.links %}
- [{{ l.label }}]({{ l.url }})
{% endfor %}
{% endif %}

{% endfor %}
