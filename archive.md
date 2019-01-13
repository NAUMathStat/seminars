---
layout: page
title: Archive
---

Note that pages and posts are listed in reverse chronological order.

### Seminars ###
- Department Colloquium
    - [Spring 2019]({{ site.baseurl }}/colloquiumSpring2019)
    - [Fall 2018]({{ site.baseurl }}/colloquiumFall2018)
    - [Spring 2018]({{ site.baseurl }}/colloquiumSpring2018)
    - [Fall 2017]({{ site.baseurl }}/colloquiumFall2017)
    - [Spring 2017]({{ site.baseurl }}/colloquiumSpring2017)
    - [Fall 2016]({{ site.baseurl }}/colloquiumFall2016)
    - [Spring 2016]({{ site.baseurl }}/colloquiumSpring2016)
    - [Fall 2015]({{ site.baseurl }}/colloquiumFall2015)
    - [Spring 2015]({{ site.baseurl }}/colloquiumSpring2015)
- Algebra, Combinatorics, Geometry, and Topology (ACGT) Seminar
    - [Spring 2019]({{ site.baseurl }}/acgtSpring2019)
    - [Fall 2018]({{ site.baseurl }}/acgtFall2018)
    - [Spring 2018]({{ site.baseurl }}/acgtSpring2018)
    - [Fall 2017]({{ site.baseurl }}/acgtFall2017)
    - [Spring 2017]({{ site.baseurl }}/acgtSpring2017)
    - [Fall 2016]({{ site.baseurl }}/acgtFall2016)
    - [Spring 2016]({{ site.baseurl }}/acgtSpring2016)
    - [Fall 2015]({{ site.baseurl }}/acgtFall2015)
    - [Spring 2015]({{ site.baseurl }}/acgtSpring2015)
- Applied Math Seminar (AMS)
    - [Spring 2019]({{ site.baseurl }}/amsSpring2019)
    - [Fall 2018]({{ site.baseurl }}/amsFall2018)
    - [Spring 2018]({{ site.baseurl }}/amsSpring2018)
    - [Fall 2017]({{ site.baseurl }}/amsFall2017)
    - [Spring 2017]({{ site.baseurl }}/amsSpring2017)
    - [Fall 2016]({{ site.baseurl }}/amsFall2016)
    - [Spring 2016]({{ site.baseurl }}/amsSpring2016)
    - [Fall 2015]({{ site.baseurl }}/amsFall2015)
    - [Spring 2015]({{ site.baseurl }}/amsSpring2015)
- Friday Afternoon Mathematics Undergraduate Seminar (FAMUS)
    - [Spring 2019]({{ site.baseurl }}/famusSpring2019)
    - [Fall 2018]({{ site.baseurl }}/famusFall2018)
    - [Spring 2018]({{ site.baseurl }}/famusSpring2018)
    - [Fall 2017]({{ site.baseurl }}/famusFall2017)
    - [Spring 2017]({{ site.baseurl }}/famusSpring2017)
    - [Fall 2016]({{ site.baseurl }}/famusFall2016)
    - [Spring 2016]({{ site.baseurl }}/famusSpring2016)
    - [Fall 2015]({{ site.baseurl }}/famusFall2015)
    - [Spring 2015]({{ site.baseurl }}/famusSpring2015)
- Teaching Showcase
    - [Fall 2015]({{ site.baseurl }}/teachingFall2015)
    - [Spring 2015]({{ site.baseurl }}/teachingSpring2015)
    - [Fall 2014]({{ site.baseurl }}/teachingFall2014)

### Weekly Posts ###
{% for post in site.posts %}
- {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ site.baseurl }}/{{ post.url }})
{% endfor %}
