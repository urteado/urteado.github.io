---
layout: archive
title: "publications"
author_profile: true
permalink: /publications/

---
- &quot;High-dimensional robust regression under heavy-tailed data: Asymptotics and Universality&quot;, Adomaityte, U., Defilippis, L., Loureiro, B., Sicuro, G., to be presented at [HeavyTails Workshop]{https://sites.google.com/view/heavy-tails-ml-2023/home} at NeurIPS 2023, under review
[[[arxiv](https://arxiv.org/abs/2309.16476)]

- &quot;Classification of Heavy-tailed Features in High Dimensions: a Superstatistical Approach&quot;, Adomaityte, U., Sicuro, G., Vivo, P., NeurIPS 2023 (poster)
[[OpenReview](https://neurips.cc/virtual/2023/poster/70963) [arxiv](https://arxiv.org/abs/2304.02912)]

- &quot;Unveiling the Hessian's Connection to the Decision Boundary&quot;, Sabanayagam, M., Behrens, F., Adomaityte, U., Dawid, A., to be presented at [M3L Workshop]{https://sites.google.com/view/m3l-2023} at NeurIPS 2023, under review
[[arxiv](https://arxiv.org/abs/2306.07104)]

- &quot;Planted matching problems on random hypergraphs&quot;, Adomaityte, U., Toshniwal, A., Sicuro, G., Zdeborová, L. (2022). Physical Review E 
[[paper](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.106.054302) [arxiv](https://arxiv.org/abs/2209.03423)]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
