---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<p><emphasize>*Denotes equal contribution.</emphasize></p>
<p><emphasize>^Denotes equal advising.</emphasize></p>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
