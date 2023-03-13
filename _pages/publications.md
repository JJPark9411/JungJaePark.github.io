---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

Journal
---
---
<ol reversed>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li></li>
  <li><b><u>Jung Jae Park</u><sup>†</sup></b>, Phillip Won<sup>†</sup>, and Seung Hwan Ko, "A Review on Hierarchical Origami and Kirigami Structure for Engineering Applications”, <i>International Journal of Precision Engineering and Manufacturing-Green Technology</i>, 6(1), 147-161, 2019.</li>
      (Symbol † indicates equal contribution as the first author.)
</ol> 


Conference
---
---

Patent
---
---



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
