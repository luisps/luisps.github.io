---
layout: single
title: "Publications"
permalink: /publications/
---

This page lists a **selected** set of publications. For a full list and citation metrics, see [Google Scholar]({{ site.data.profile.scholarUrl }}).

{% assign pubs = site.data.publications | sort: 'year' | reverse %}
{% assign current_year = nil %}

{% for p in pubs %}
  {% if p.year != current_year %}

### {{ p.year }}
  {% assign current_year = p.year %}
  {% endif %}

- **{{ p.title }}**  
  {{ p.authors }}  
  *{{ p.venue }}*
  {% if p.doi %} · DOI: [{{ p.doi }}](https://doi.org/{{ p.doi }}){% endif %}
  {% if p.handle %} · [Repository link]({{ p.handle }}){% endif %}
  {% if p.tags %}  
  <small>{{ p.tags | join: " · " }}</small>
  {% endif %}

{% endfor %}
