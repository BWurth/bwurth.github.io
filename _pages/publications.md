---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order. Please get in touch via email if you cannot access any publications but want a copy.
bib_search_in_header: true
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

## Working Papers / Work in Progress

<div class="publications wip-section">
{% bibliography -f working_papers --group_by none --template bib-wip --query @*[status=under_review]* --sort year --order descending %}
{% bibliography -f working_papers --group_by none --template bib-wip --query @*[status=working_paper]* --sort year --order descending %}
{% bibliography -f working_papers --group_by none --template bib-wip --query @*[status=work_in_progress]* --sort year --order descending %}
</div>

## Publications

<div class="publications">

{% bibliography %}

</div>
