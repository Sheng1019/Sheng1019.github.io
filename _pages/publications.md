---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
  Summary: 16 papers are published and 1 paper is under reviewing. 8 published papers belong to
the selective conferences in CSRanking, where 6 of them are first/co-first authored papers (leader) or
the second author (main contributor) under the Design Automation area (i.e., DAC, ICCAD), 2 papers
are published at the top conference on medical image processing (i.e., MICCAI).
{% endif %}



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
