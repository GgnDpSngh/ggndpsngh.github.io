---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<h2> Preprints</h2>
<h3> Syndicate: Synergistic Synthesis of Ranking Function and Invariants for Termination Analysis
  <a href= "https://arxiv.org/pdf/2404.05951.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p> Yasmin Sarita, Avaljot Singh, Shaurya Gomber, Gagandeep Singh, Mahesh Vishwanathan, Arxiv 2024.</p>

<h3> ConstraintFlow: A DSL for Specification and Verification of Neural Network Analyses 
  <a href= "https://arxiv.org/pdf/2403.18729.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Avaljot Singh, Yasmin Sarita, Charith Mendis, Gagandeep Singh, Arxiv 2024.</p>


<h3>Improving LLM Code Generation with Grammar Augmentation  
  <a href= "https://arxiv.org/abs/2403.01632"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Shubham Ugare, Tarun Suresh, Hangoo Kang, Sasa Misailovic, Gagandeep Singh, Arxiv 2024.</p>

<h3>Reward Poisoning Attack Against Offline Reinforcement Learning  
  <a href= "https://arxiv.org/abs/2402.09695"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Yinglun Xu, Rohan Gumaste, Gagandeep Singh, Arxiv 2024.</p>

<h3>RAMP: Boosting Adversarial Robustness Against Multiple Lp Perturbations  
  <a href= "https://arxiv.org/abs/2402.06827"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Enyi Jiang, Gagandeep Singh, Arxiv 2024.</p>

<h3>Efficient Two-Phase Offline Deep Reinforcement Learning from Preference Feedback  
  <a href= "https://arxiv.org/abs/2401.00330"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Yinglun Xu, Gagandeep Singh, Arxiv 2024.</p>


<h3>
Black-Box Targeted Reward Poisoning Attack Against Online Deep Reinforcement Learning 
  <a href= "https://arxiv.org/abs/2305.10681"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Yinglun Xu, Gagandeep Singh, Arxiv 2023.</p>

<h3>
Robust Universal Adversarial Perturbations 
  <a href= "https://arxiv.org/pdf/2206.10858.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Changming Xu, Gagandeep Singh, Arxiv 2023.</p>

<h2> Workshops and Short Papers</h2>

<h3>QuaCer-C: Quantitative Certification of Knowledge Comprehension in LLMs 
  <a href= "https://arxiv.org/abs/2402.15929"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Isha Chaudhary, Vedaant Jain, Gagandeep Singh, SeT LLM@ICLR 2024.</p>

<h3>Bypassing the Safety Training of Open-Source LLMs with Priming Attacks  
  <a href= "https://arxiv.org/abs/2312.12321"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Jason Vega, Isha Chaudhary, Changming Xu, Gagandeep Singh, Tiny Papers@ICLR 2024.</p>

<h3>Exploiting Time Channel Vulnerability of Learned Bloom Filters 
  <a href= ""><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Harman Singh Farwah, Gagandeep Singh, Cheng Tan, Tiny Papers@ICLR 2024.</p>

<h3>Is Watermarking LLM-Generated Code Robust?  
  <a href= "https://arxiv.org/pdf/2403.17983.pdf"><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Tarun Suresh, Shubham Ugare, Gagandeep Singh, Sasa Misailovic, Tiny Papers@ICLR 2024.</p>

<h3>
Abstract Interpretation for Automatic Differentiation
  <a href= ""><i class="fas fa-fw fa-link zoom" aria-hidden="true"></i></a></h3>
<p>Jacob Laurel, Siyuan Brant Qian, Gagandeep Singh, Sasa Misailovic, LAFI@POPL 2024.</p>

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
