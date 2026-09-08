---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}


{% include section.html %}

# Current Members

{% include list.html data="members" component="portrait" filter="(group == 'postdoc' or group == 'phd' or group == 'phd-co' or group == 'mphil' or group == 'msc' or group == 'ug') and role != 'pi'" %}


{% include section.html %}

# Alumni

{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}
