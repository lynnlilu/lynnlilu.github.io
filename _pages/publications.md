---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Conference Papers
======
{% for post in site.publications/conference reversed %}
  {% include archive-single.html %}
{% endfor %}

Journal Papers
======
{% for post in site.publications/journal reversed %}
  {% include archive-single.html %}
{% endfor %}
