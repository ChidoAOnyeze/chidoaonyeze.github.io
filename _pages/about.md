---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 3rd year Computer Science Ph.D. student at Cornell University. I am fortunate to be advised by <a href="https://www.cs.cornell.edu/~eva/">Éva Tardos</a>. My research interests lie in Game Theory, Learning in Games and Resource Allocation Problems. 

Before starting at Cornell, I recieved a Bachelors Degree in Computer Science and Mathematics from Georgia Tech where I worked with Dr. Cassie S. Mitchell, Dr. Prasad Tetali and Dr. Lutz Warnke on various projects in Extremal Combinatorics and Randomized Algorithms.

<div style="border-top: 2px solid #ccc; margin: 20px 0;"></div>

News
=====

<ul class="updates-list" style="list-style-type: none;">
{% for update in site.updates reversed %}
  {% include update_item.html date=update.content_date content=update.content_body %}
{% endfor %}
</ul>

<div style="border-top: 2px solid #ccc; margin: 20px 0;"></div>

Publications
=====

<ul style="list-style-type: none;" class="publications-list">
  {% for publication in site.publications reversed %}
    {% include publication_item.html title=publication.title authors=publication.authors venue=publication.venue external_reference=publication.external_reference publication_year=publication.publication_year %}
  {% endfor %}
</ul>