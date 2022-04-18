---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2022, 2021, 2020, 2019, 2018, 2017, 2016]
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

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f journal -q @*[year={{y}}]* %}
  {% endfor %}

</div>

[^_^]:[^_^]:<!-- #### Preprints and submissions -->
[^_^]:<!-- 1. Pooladian, A-A., and Niles-Weed, J. "Entropic estimation of optimal transport maps" (2021) [<a href="https://arxiv.org/pdf/2109.12004.pdf">PDF</a>]

[^_^]:#### Conference papers
[^_^]:1. Pooladian, A-A.\*, Finlay, C., Hoheisel, T., and Oberman, A. "A principled approach for generating adversarial images under non-smooth dissimilarity metrics", in *23rd International Conference on Artificial Intelligence and Statistics (AISTATS 2020)*. [<a href="https://github.com/APooladian/FarkasLayers">Github</a>] [<a href="https://arxiv.org/pdf/1908.01667.pdf">PDF</a>]

[^_^]:#### Workshop papers
[^_^]:1. Finlay, C.\*, Gerolin, A.\*, Oberman, A., Pooladian A-A.\* (alphabetical) "Learning normalizing flows from Entropy-Kantorovich potentials", in *ICML workshop on Invertible Neural Networks, Normalizing Flows, and Explicit Likelihood Models (INNF+ 2020)*, with contributing talk, [<a href="https://arxiv.org/pdf/2006.06033.pdf">PDF</a>]

#### Journal articles
1. T. Li, Y. Jiang, C. Lin, M. Obaidat, Y. Shen and J. Ma, "DeepAG: Attack Graph Construction and Threats Prediction with Bi-directional Deep Learning," in IEEE Transactions on Dependable and Secure Computing, doi: 10.1109/TDSC.2022.3143551.

[^_^]:#### Deep learning projects
[^_^]:1. Pooladian, A-A.\*, Finlay, C., and Oberman, A., "Farkas layers: Don't shift the data, fix the geometry" (2019) [<a href="https://github.com/APooladian/FarkasLayers">Github</a>] [<a href="https://arxiv.org/pdf/1910.02840.pdf">PDF</a>]
