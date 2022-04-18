---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2022]
nav: true
---

[[Conference papers](#conference-papers)] | [[Journal papers](#journal-papers)]

[^_^]:#### Books

[^_^]:<div class="publications">

[^_^]:{% for y in page.years %}
 [^_^]: {% bibliography -f books -q @*[year={{y}}]* %}
[^_^]:{% endfor %}

[^_^]:</div>


[^_^]:#### Conference papers

[^_^]:<div class="publications">

[^_^]:{% for y in page.years %}
 [^_^]: <h2 class="year">{{y}}</h2>
[^_^]:  {% bibliography -f confs -q @*[year={{y}}]* %}
[^_^]:{% endfor %}

[^_^]:</div>

#### Journal papers

[^_^]:<div class="publications">

[^_^]:{% for y in page.years %}
  [^_^]:<h2 class="year">{{y}}</h2>
  [^_^]:{% bibliography -f journal -q @*[year={{y}}]* %}
  [^_^]:{% endfor %}

[^_^]:</div>

[^_^]:[^_^]:<!-- #### Preprints and submissions -->
[^_^]:<!-- 1. Pooladian, A-A., and Niles-Weed, J. "Entropic estimation of optimal transport maps" (2021) [<a href="https://arxiv.org/pdf/2109.12004.pdf">PDF</a>]

[^_^]:#### Conference papers
[^_^]:1. 

[^_^]:#### Workshop papers
[^_^]:1. 

[^_^]:#### Journal articles
1. T. Li, Y. Jiang, C. Lin, M. Obaidat, Y. Shen and J. Ma, "DeepAG: Attack Graph Construction and Threats Prediction with Bi-directional Deep Learning," in IEEE Transactions on Dependable and Secure Computing, doi: 10.1109/TDSC.2022.3143551.

[^_^]:#### Deep learning projects
[^_^]:1. 
