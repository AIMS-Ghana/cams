---
title: Practicals
---

The practical exercises, in order:

{% for i in (1..site.practice.size) %}
 - {% include prac_link.md which = forloop.index0 %}{% endfor %}