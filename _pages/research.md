---
layout: archive
title: "Works In Progress"
permalink: /works_in_progress/
author_profile: true
---
---
layout: archive
title: "Research Assistant Work"
permalink: /research_assistant/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
