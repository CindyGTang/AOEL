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

{% include list.html data="members" component="portrait" filter="group !='alumni' and role != 'pi'" %}


{% include section.html %}

# Alumni

{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}
