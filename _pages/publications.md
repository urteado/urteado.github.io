---
layout: archive
title: "Publications"
author_profile: true
permalink: /publications/

---
### Preprints:
- &quot;PCA recovery thresholds in low-rank matrix inference with sparse noise&quot;, Adomaityte, U., Sicuro, G., Vivo, P., [arxiv](https://arxiv.org/abs/2511.11927) 

### Peer-reviewed:

- &quot;High-dimensional robust regression under heavy-tailed data: Asymptotics and Universality&quot;, Adomaityte, U., Defilippis, L., Loureiro, B., Sicuro, G., J. Stat. Mech. Machine Learning 2024 Special Issue (2024), also [HeavyTails Workshop](https://sites.google.com/view/heavy-tails-ml-2023/home) paper at NeurIPS 2023
[[J.Stat.Mech.](https://iopscience.iop.org/article/10.1088/1742-5468/ad65e6) [arxiv](https://arxiv.org/abs/2309.16476)]

- &quot;Classification of Heavy-tailed Features in High Dimensions: a Superstatistical Approach&quot;, Adomaityte, U., Sicuro, G., Vivo, P., NeurIPS 2023 main track
[[NeurIPS](https://neurips.cc/virtual/2023/poster/70963) [arxiv](https://arxiv.org/abs/2304.02912)]

- &quot;Planted matching problems on random hypergraphs&quot;, Adomaityte, U., Toshniwal, A., Sicuro, G., Zdeborová, L. (2022). Physical Review E 
[[paper](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.106.054302) [arxiv](https://arxiv.org/abs/2209.03423)]

### Workshop papers:

- &quot;Unveiling the Hessian's Connection to the Decision Boundary&quot;, Sabanayagam, M., Behrens, F., Adomaityte, U., Dawid, A., [M3L Workshop](https://sites.google.com/view/m3l-2023) paper at NeurIPS 2023,
[[arxiv](https://arxiv.org/abs/2306.07104)]

### Lecture notes:
- &quot;Replica method for computational problems with randomness: principles and illustrations&quot;, J Steinberg, U Adomaitytė, A Fachechi, P Mergny, D Barbier and R Monasson, J. Stat. Mech. (2024), Special Issue for the Summer school on Statistical Physics & Machine learning, Les Houches 2022, [[J.Stat.Mech.](https://iopscience.iop.org/article/10.1088/1742-5468/ad292d/meta) [free access](https://www.phys.ens.fr/~monasson/Articles/a148.pdf)].



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
