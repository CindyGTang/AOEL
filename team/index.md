---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

Prof. Cindy G. Tang (董冠妤) received her PhD degree from the Department of Physics and her bachelor’s degree in Engineering Science at the National University of Singapore (NUS). She received the best PhD thesis award in Natural Sciences at NUS and was a recipient of the Presidential Postdoctoral Fellowship at Nanyang Technological University (NTU). She has published her research as in several high-impact journals including Nature, Nature Communications, Advanced Materials, Advanced Science, ACS Nano, Materials Horizon, etc.



{% include section.html %}

# Current Members

{% data="members" component="portrait" filter="group !='alumni' and role != 'pi'" %}


{% include section.html %}

# Alumni

{% data="members" component="portrait" filter="group == 'alumni'" %}
