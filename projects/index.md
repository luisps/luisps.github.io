---
layout: single
title: "Projects"
permalink: /projects/
---

{% for p in site.data.projects %}
### {{ p.title }}

{{ p.meta }}

{{ p.description }}

{% if p.links and p.links.size > 0 %}
Links:
{% for l in p.links %}
- [{{ l.label }}]({{ l.url }})
{% endfor %}
{% endif %}

{% endfor %}
