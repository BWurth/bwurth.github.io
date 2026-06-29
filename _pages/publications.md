---
layout: page
permalink: /publications/
title: Publications
description: Publications by categories in reversed chronological order. Please get in touch via email if you cannot access any publications but want a copy.
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

{% include bib_search.liquid %}

## Working Papers / Work in Progress

<div class="publications">
{% bibliography -f working_papers --group_by none --template bib-wip --sort year --order descending %}
</div>

## Publications

<div class="publications">

{% bibliography %}

</div>