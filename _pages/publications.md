---
layout: page
permalink: /publications/
title: publications
description: Publications in reversed chronological order
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">
  <h2>First- and co-first-authored. #: equal contributions</h2>
  {% bibliography --query @*[keywords=first-authored] %}
  
  <h2>Co-authored:</h2>
  {% bibliography --query @*[keywords=co-authored] %}

  <h2>Theses and Patents</h2>
  {% bibliography --query @*[keywords=thesis] %}
</div>
