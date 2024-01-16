---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<h1> Preprints</h1>
<h2>Bypassing the Safety Training of Open-Source LLMs with Priming Attacks  
  <a href= "https://arxiv.org/abs/2312.12321"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h2>
<p>Jason Vega, Isha Chaudhary, Changming Xu, and Gagandeep Singh, Arxiv 2024.</p>

<h2>
Black-Box Targeted Reward Poisoning Attack Against Online Deep Reinforcement Learning 
  <a href= "https://arxiv.org/abs/2305.10681"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h2>
<p>Yinglun Xu, Gagandeep Singh, Arxiv 2023.</p>

<h2>
Robust Universal Adversarial Perturbations 
  <a href= "https://arxiv.org/pdf/2206.10858.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h2>
<p>Changming Xu, Gagandeep Singh, Arxiv 2023.</p>

<h1> Workshops</h1>

<h2>
CoMEt: x86 Cost Model Explanation Framework
  <a href= "https://arxiv.org/abs/2302.06836"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h2>
<p>Isha Chaudhary, Alex Renda, Charith Mendis, Gagandeep Singh, XAIA@NeurIPS 2023.</p>


<h1> Conferences and Journals</h1>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
