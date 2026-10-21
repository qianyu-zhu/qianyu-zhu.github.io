---
layout: page
permalink: /publications/
title: Publications
description:
nav: true
nav_order: 1
---
<!-- Entry order in papers.bib is intentional; do not regroup by year. -->
<div class="publications">

<h2 id="statistics">Statistics</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=statistics] --group_by none %}

<h2 id="math">Math</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=math] --group_by none %}

<h2 id="language-models">Language Models</h2>
{% bibliography -f {{ site.scholar.bibliography }} --query @*[category=language-models] --group_by none %}

</div>
