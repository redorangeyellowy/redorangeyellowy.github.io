---
layout: default
title: Home
---

# 주요 논문 소개

<div class="paper-list">
  {% for paper in site.data.papers %}
    {% include paper_card.html paper=paper %}
  {% endfor %}
</div>
