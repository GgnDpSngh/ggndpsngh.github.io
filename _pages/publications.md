---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<h2> Preprints</h2>
<p>
Black-Box Targeted Reward Poisoning Attack Against Online Deep Reinforcement Learning  
  <a href= "https://arxiv.org/abs/2305.10681"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></p>
<p>Yinglun Xu, Gagandeep Singh, Arxiv 2023</p>
<h2> Peer Reviewed at Conferences and Journals</h2>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
