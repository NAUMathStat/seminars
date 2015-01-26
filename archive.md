---
layout: page
title: Archive
---

## Seminars ##
- [Department Colloquium]({{ site.baseurl }}/colloquium)
- [Algebra, Combinatorics, Geometry, and Topology (ACGT) Seminar]({{ site.baseurl }}/acgt)
- [Applied Math Seminar (AMS)]({{ site.baseurl }}/ams)
- [Friday Afternoon Mathematics Undergraduate Seminar (FAMUS)]({{ site.baseurl }}/famus)
- [Teaching Showcase]({{ site.baseurl }}/teaching)

{% for page in site.pages_list %}
- <a href="{{ page[1]  }}">{{ page[0] }}</a>
{% endfor %}

## Weekly Posts ##
{% for post in site.posts %}
- {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
