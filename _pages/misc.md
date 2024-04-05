---
permalink: /#-misc
title: ""
excerpt: ""
author_profile: true
---
# Miscellaneous

{% include base_path %}

{% for post in site.archive %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}