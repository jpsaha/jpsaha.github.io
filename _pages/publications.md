---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please visit the page 
[https://jpsaha.github.io/MOTP/MOPSS/](https://jpsaha.github.io/MOTP/MOPSS/).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!--
<sup>*</sup> Equal authorship
-->
