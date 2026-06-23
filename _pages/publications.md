---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
hide_title: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication-single.html %}
{% endfor %}
