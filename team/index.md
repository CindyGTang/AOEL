---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

Current members

{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html %}

Alumni

{% include section.html %}

{% include list.html data="members" component="portrait" filter="group = 'alumni'" %}
