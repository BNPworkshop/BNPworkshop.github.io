---
layout: front
permalink: /
title: Princeton Bayesian Nonparametric Workshop
image:
  feature: cover-princeton-07.jpg
---
<h4>Introduction</h4>

<p>
	Nonparametric Bayesian methods are data analytic tools applicable to students in a variety of disciplines.  Nonparametric Bayesian methods make use of infinite-dimensional mathematical structures to allow the practitioner to learn more from their data as the size of their data set grows. This tutorial, will cover why machine learning and statistics need more than just parametric Bayesian inference and will introduce foundational nonparametric Bayesian models as the Dirichlet process and Chinese restaurant process and touch on the wide variety of models available in nonparametric Bayes. It will show exactly what nonparametric Bayesian methods are and what they accomplish.
</p>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

