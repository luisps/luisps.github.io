---
layout: single
title: "Students"
permalink: /students/
---

## Supervision at a glance

{% for s in site.data.students.stats %}
- **{{ s.label }}:** {{ s.value }}
{% endfor %}

## Current PhD students

{% for st in site.data.students.currentPhD %}
- **{{ st.name }}**  
  {{ st.program }}  
  *Topic:* {{ st.topic }}
{% endfor %}

> If you are one of my students and want your personal webpage link added here, send me the URL and I will update this list.
