---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

<h2>Ph.D. thesis</h2>

{% bibliography -f thesis --group_by type %}

<hr class="section-divider">

<h2>preprints</h2>

{% bibliography -f preprints --group_by type %}

<hr class="section-divider">

<h2>conference &amp; journal articles</h2>

{% bibliography -f papers --group_by type %}

<hr class="section-divider">



</div>
