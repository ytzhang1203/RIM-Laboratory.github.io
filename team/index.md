---
title: Team
nav:
  order: 3
  tooltip: About our team
---

## Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}

{% include list.html data="members" component="portrait" filters="status: active" %}

{% include section.html %}

#### Alumni

{% include list.html data="members" component="portrait" filters="status: alumni" %}

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
