---
layout: default
title: Arindam Paul
---

<div class="intro" align="justify">
	<h1 class="pageTitle"><font color="green">Software Quality Estimation using Fuzzy Logic</font></h1>
	<p>Revolution brought about by the IT industry in the past decade led to increase in the importance of software quality.However, a study conducted by NIST (National Institute of Standards and Technology) in 2002 reports that software bugs cost the U.S. economy $59.5 billion annually. Measure of how successful depends on how much the software is able to meet the needs and demands of users and achieving the goals of developers. It also depends on the conformity to the explicitly stated functional and performance requirement. Every metric, sub characteristic and characteristic is associated with its corresponding rating and weight. Both rating and weight are triangular fuzzy sets as shown below:</p>
	<p align ="center"><img src="{{ '/assets/img/fuzzy2.png' | prepend: site.baseurl }}" alt="" height="280" width="350"></p>

	<p>Ratings are calculated using the fuzzy rule base and weights are taken from the users, developers and project managers respectively. Every parameter in the entire model is quantified in the range 0 to 1. Fuzzy Weighted Average of all the quantified criteria and sub criteria is taken in order to evolve the final quality. Following is a sub-usecase of the quality Security.
</p>

	<p align="center"><img src="{{ '/assets/img/fuzzy1.png' | prepend: site.baseurl }}" alt="" height="280" width="350">


	<p>Now we multiply the ratings with their respective weights. And, we multiply the ratings with their respective weights. We use the centroid formula to convert fuzzy to crisp:
<p align="center"><font color="green">Centroid Formula – z*</font> = (∫ µ(z) . z . dz)/
					  ( ∫ µ(z) . dz)

</p>
	<p align="center"><img src="{{ '/assets/img/fuzzy3.png' | prepend: site.baseurl }}" alt="" height="315" width="420"></p>
	<p>We evaluate this software on three software – </p>
<p style="color:purple;" align="center">Course Management Tool (CMT)<br>
Auto-ID<br>
Income Tax Calculator.</p>

<p>We evaluate software quality by taking inputs from developers, users and Project Manager separately and finally the entire software quality. The work can be extended using considering more number of attributes or metrics to quantify the software quality.
</p>
</div>
<h4><font color="purple" >Publications: </font></h4>
<p>J.S. Challa,<b>A. Paul</b>, Y.Dada, V.Nerella, P.R. Srivastava and A.P.Singh <a href="/assets/pdf/ISQE.pdf" style="text-decoration:none" onmouseover="this.style.textDecoration = 'underline'" onmouseout="this.style.textDecoration = 'none'"><font color="green">Integrated Software Quality Evaluation: A Fuzzy Multi-Criteria Approach</font></a>, <i> Journal of Information Processing Systems (JIPS) 2011 Volume 7 </i></p>

<p>J.S. Challa,<b>A. Paul</b> ,Y. Dada, V. Nerella, P.R. Srivastava <a href="/assets/pdf/QSQ.pdf" style="text-decoration:none" onmouseover="this.style.textDecoration = 'underline'" onmouseout="this.style.textDecoration = 'none'" ><font color="green">Quantification of Software Quality Parameters using Fuzzy Multi-Criteria Approach</font></a>, <i>  IEEE International Conference on Process Automation Control and Computing (PACC) 2011</i></p>
