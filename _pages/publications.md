---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<h2> Preprints</h2>
<h3>Efficient Two-Phase Offline Deep Reinforcement Learning from Preference Feedback  
  <a href= "https://arxiv.org/abs/2401.00330"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Yinglun Xu, and Gagandeep Singh, Arxiv 2024.</p>


<h3>Bypassing the Safety Training of Open-Source LLMs with Priming Attacks  
  <a href= "https://arxiv.org/abs/2312.12321"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Jason Vega, Isha Chaudhary, Changming Xu, and Gagandeep Singh, Arxiv 2024.</p>

<h3>
Black-Box Targeted Reward Poisoning Attack Against Online Deep Reinforcement Learning 
  <a href= "https://arxiv.org/abs/2305.10681"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Yinglun Xu, Gagandeep Singh, Arxiv 2023.</p>

<h3>
Robust Universal Adversarial Perturbations 
  <a href= "https://arxiv.org/pdf/2206.10858.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Changming Xu, Gagandeep Singh, Arxiv 2023.</p>

<h2> Workshops</h2>


<h3>
Abstract Interpretation for Automatic Differentiation
  <a href= ""><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Jacob Laurel, Siyuan Brant Qian, Gagandeep Singh, Sasa Misailovic, LAFI@POPL 2024.</p>

<h3>
CoMEt: x86 Cost Model Explanation Framework
  <a href= "https://arxiv.org/abs/2302.06836"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Isha Chaudhary, Alex Renda, Charith Mendis, Gagandeep Singh, XAIA@NeurIPS 2023.</p>

<h3>
Toward Continuous Verification of DNNs
  <a href= "https://shubhamugare.github.io/assets/pdf/ICML_workshop.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Shubham Ugare, Debangshu Banerjee, Tarun Suresh, Sasa Misailovic, Gagandeep Singh, WFVML@ICML 2023.</p>

<h3>
Property-Driven Evaluation of RL-Controllers in Self-Driving Datacenters 
  <a href= "https://ggndpsngh.github.io/files/DMML.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Arnav Chakravarthy, Nina Narodytska, Asmitha Rathis, Marius Vilcu, Mahmood Sharif, Gagandeep Singh, DMML@NeurIPS 2022.</p>


<h3>
Physically-Constrained Adversarial Attacks on Brain-Machine Interfaces 
  <a href= "https://ggndpsngh.github.io/files/TSRML.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Xiaying Wang, Rodolfo Octavio Siller Quintanilla, Michael Hersche, Luca Benini, Gagandeep Singh, TSRML@NeurIPS 2022.</p>

<h2> Conferences and Journals</h2>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
