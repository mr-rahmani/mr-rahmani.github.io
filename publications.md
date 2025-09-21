---
layout: page
title: Publications
permalink: /publications/
---

<ul class="pub-list">
{% bibliography --group_by year --group_order descending %}
</ul>

## By Type
### Journal Articles
<ul class="pub-list">
{% bibliography --query @article %}
</ul>

### Conference Papers
<ul class="pub-list">
{% bibliography --query @inproceedings %}
</ul>
