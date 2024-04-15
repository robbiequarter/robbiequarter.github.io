---
layout: archive
title: "THINGS I'VE WRITTEN"
header:
  overlay_image: header_image.jpg
  overlay_filter: 0.3
excerpt: <br>
permalink: /publications/
author_profile: true
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=rovpQCwAAAAJ&hl=en">my Google Scholar profile</a>. Reach out if you can't access or find a full article!

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
