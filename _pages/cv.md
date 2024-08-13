---
layout: archive
#title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Probability and Mathematical Satistics, Peking University, 2027 (expected)
* B.S. in Mathematics and Applied Mathematics, Peking University, 2022

Research Interests
======
* Schramm-Loewner Evolution; Liouville quantum gravity;
* Critical statistical physics models; Conformal field theory.

Awards and Honors
======
* President Scholarship, Peking University, 2022
* Excellent Graduate, Peking University, 2022

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
