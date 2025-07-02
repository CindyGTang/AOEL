---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

<div>
  {% for link in page.links %}
    {% assign key = link[0] %}
    {% assign value = link[1] %}
    {% include button.html type=key link=value style="bare" %}<br>
  {% endfor %}
</div>

{% include section.html %}

# Current Members

{% include list.html data="members" component="portrait" filter="group !='alumni' and role != 'pi'" %}


{% include section.html %}

# Alumni

{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}
