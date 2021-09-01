---
title: Logic and Artificial Intelligence
collection: teaching
type: "Advanced Graduate course"
ref: lai2021
description: Advanced graduate course discussing the latest advances in combining logical reasoning with traditional data-driven methods.
semester: Fall 2021
lecturer: Gagandeep Singh
date: 2021-08-25 
head-ta: Linyi Li 
head-ta-url: http://www.linyil.com/
venue: "Wed, Fri 11-12:15 pm, 0216 Siebel Center for Comp Sci"
credits: 4
---

<h2>Overview</h2>

<p>
  Given the black-box nature of the state-of-the-art AI models and the lack of associated formal guarantees, there is a growing interest in using formal methods for AI-based systems to ensure their reliability and interpretability. 
  This direction is a key component of the so-called “Third wave of AI”. Similarly, there is a growing interest in leveraging data-driven machine learning for knowledge discovery and boosting logical inference. 
  This course will introduce recent developments in both directions and outline several promising future research directions. Overall, the students will be exposed to the following topics:
</p>


<ul>

<li>Verification of AI systems</li>
<li>Symbolic explanations of neural networks</li>
<li>Training and querying with logic</li>
<li>Robust training methods</li>
  <li>Neural network repair</li>
	<li>Probabilistic circuits</li>
<li>Neurosymbolic computing </li>
<li>Machine learning for verification</li>


</ul>
The course will be taught in person. For students preferring to attend remotely, the video recording of the lectures will be made available online. 

<h2 id="lectures">Lectures</h2>
<table centering border="0" width="100%" cellspacing="0" cellpadding="0">

	<th width="15%">Date</th>
	<th width="40%">Title</th>
	<th width="10%">Slides</th>
	<th width="50%"> Reading material </th>

<tr>
	<td>Aug 25, 27</td>
	<td>Introduction</td>  
	<td><a href="/slides/lai21/lai-intro.pptx" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	
	<tr>
	<td>Sep 1, 3</td>
	<td>Verification of neural networks: Box + MILP</td>  
	<td><a href="" class="pdf" title="Box + MILP"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td>
		<p>Box<a href="https://arxiv.org/pdf/1804.10829.pdf" class="pdf" title="Box + MILP"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p>
		<p>MILP<a href="https://arxiv.org/abs/1711.07356" class="pdf" title="Box + MILP"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p>
		</td>  
</tr>
	
	<tr>
	<td>Sep 8, 10</td>
	<td>Verification of neural networks: Zonotopes</td>  
	<td><a href="" class="pdf" title="zonotopes"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td>
		<p>Zonotopes <a href="https://www.sri.inf.ethz.ch/publications/gehr2018ai" class="pdf" title="zonotopes"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
		<a href="/files/DeepZ.pdf" class="pdf" title="zonotopes"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p>
		</td>
</tr>
	<tr>
	<td>Sep 15, 17</td>
	<td> Verification of neural networks: DeepPoly + Refinement</td>  
	<td><a href="" class="pdf" title="DeepPoly"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td><p>DeepPoly<a href="/files/DeepPoly.pdf" class="pdf" title="Deeppoly"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p>
		<p>Refinement<a href="/files/RefineZono.pdf" class="pdf" title="Refinement"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p>
		</td>
</tr>
	<tr>
	<td>Sep 22</td>
	<td>Project presentation</td>  
	<td><a href="" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	<tr>
	<td>Sep 24</td>
	<td>Verification of neural networks: k-ReLU</td>  
	<td><a href="" class="pdf" title="krelu"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td><p>k-ReLU<a href="/files/neurips19_krelu.pdf" class="pdf" title="krelu"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p></td>
</tr>
	<tr>
	<td>Sep 29, Oct 01</td>
	<td>Symbolic explanation of neural networks</td>  
	<td><a href="" class="pdf" title="symex"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td><p>Symbolic explanation<a href="https://arxiv.org/pdf/1802.07384.pdf" class="pdf" title="symex"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p></td>
</tr>
	<tr>
	<td>Oct 06, 08</td>
	<td>Training and querying with Logic</td>  
	<td><a href="" class="pdf" title="dl2"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td><p>DL2<a href="http://proceedings.mlr.press/v97/fischer19a/fischer19a.pdf" class="pdf" title="dl2"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p></td>
</tr>
	<tr>
	<td>Oct 13, 15</td>
	<td>Robust training of neural networks</td>  
	<td><a href="" class="pdf" title="robust training"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td>
		<p>Robust training<a href="https://arxiv.org/pdf/1810.12715.pdf" class="pdf" title="robust training"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
		<a href="https://files.sri.inf.ethz.ch/website/papers/icml18-diffai.pdf" class="pdf" title="robust training"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></p>
		</td>
</tr>
	<tr>
	<td>Oct 20, 22</td>
	<td>Neural network repair</td>  
	<td><a href="" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	<tr>
	<td>Oct 27, 29</td>
	<td>Probabilistic circuits</td>  
	<td><a href="" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	
	<tr>
	<td>Nov 03, 05</td>
	<td>Neurosymbolic computing</td>  
	<td><a href="" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	<tr>
	<td>Nov 10, 12</td>
	<td>Machine Learning for verification</td>  
	<td><a href="" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	<tr>
	<td>Nov 17, 19, Dec 01, 03, 08</td>
	<td>Student Presentations</td>  
	<td><a href="" class="pdf" title="intro"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a></td>  
	<td></td>
</tr>
	
  </table>
  
  
<h2 id="grading">Grading</h2>

The students will work in a group of 2 or individually on:
<ul>
	<li> a course project, </li>
	<li> conference-style paper presentation on one of the topics taught in the course towards the end of the semester (see dates above). The students are free to select any paper, but it must be approved by us.</li>
	</ul>

Both project and presentation will make up 50 % of the grade each. 

<h2 id="timeline"> Key Dates </h2>

<table centering border="0" width="100%" cellspacing="0" cellpadding="0">

	<th width="30%">Deadline</th>
	<th width="70%">Task</th>

<tr>
	<td>Sep 21</td>
	<td>Register your group for the project and presentation</td>  
</tr>
	<tr>
	<td>Oct 26</td>
	<td>Selecting a paper to present</td>  
</tr>
	
	<tr>
	<td>Nov 10</td>
	<td>Project submission</td>  
	
</tr>
	</table>
