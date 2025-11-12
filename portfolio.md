---
layout: default
title: Portfolio
excerpt: Selected projects.
---

## Selected projects

{% for item in site.data.portfolio %}
### {{ item.title }}
**Client:** {{ item.client }} • **Year:** {{ item.year }}

{{ item.summary }}

[View project]({{ item.link }})
{% endfor %}
