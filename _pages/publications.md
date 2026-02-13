---
layout: default
title: Publications
permalink: /publications/
description: Publications by Elizabeth A. Ronan, sorted in reverse chronological order.
nav: true
nav_order: 2
---

<div style="margin-bottom: 2rem; padding: 1rem; background-color: var(--global-bg-color); border-left: 3px solid var(--global-theme-color);">
  <strong>Related Pages:</strong>
  <a href="/preprints/" style="margin-left: 1rem;">Preprints</a> |
  <a href="/reviews/" style="margin-left: 0.5rem;">Reviews & Commentaries</a> |
  <a href="/protocols/" style="margin-left: 0.5rem;">Protocols</a>
</div>

{% include bib_search.liquid %}

<div class="publications">
{% bibliography --file papers --sort year --order descending %}
</div>
