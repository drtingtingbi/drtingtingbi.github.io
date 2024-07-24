---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on my Google Scholar profile https://scholar.google.com.au/citations?hl=en&user=0ixOsn8AAAAJ&view_op=list_works&sortby=pubdate</a>.</div>

<div class="wordwrap"> 
  
### 2024

- Toward Web3 Applications: Easing the Access and Transition. G Yu, X Wang, Q Wang, ***T Bi***, YF Dong, RP Liu, N Georgalas, A Reeves
IEEE Transactions on Computational Social Systems
- What Makes a Good TODO Comment? H Wang, Z Gao, ***T Bi***, J Grundy, X Wang, M Wu, X Yang, ACM Transactions on Software Engineering and Methodology

  
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
