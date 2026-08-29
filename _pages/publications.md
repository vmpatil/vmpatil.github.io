---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Below you can find a list of my publications, with links to the full papers.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

*Healthcare Applications of 0-1 Neural Networks in Prescriptive Problems with Observational Data*  
with: Yonatan Mintz
Health Care Management Science (2026) <a href="https://link.springer.com/article/10.1007/s10729-025-09751-5" style="font-style: normal;">(Link)</a>, <a href="https://vmpatil.github.io/files/pnn.pdf" style="font-style: normal;">(pdf)</a>   


