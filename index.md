---
layout: single
permalink: /
title: "Luís Paulo Santos"
author_profile: true
---

**{{ site.data.profile.org }}** · {{ site.data.profile.affiliations }}

## About

{{ site.data.profile.about }}

{{ site.data.profile.recentFocus }}

## Research interests
{% for item in site.data.profile.researchInterests %}
- {{ item }}
{% endfor %}

## Sections
- [Publications](/publications/)
- [Projects](/projects/)
- [Lecturing](/teaching/)
- [Students](/students/)

## Contact
- Email: [{{ site.data.profile.email }}](mailto:{{ site.data.profile.email }})
- Office: {{ site.data.profile.office }}

## External profiles
{% for l in site.data.profile.links %}
- [{{ l.label }}]({{ l.url }})
{% endfor %}
