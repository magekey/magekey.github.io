---
layout: extension
title: Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.promotion_banner %}
{% assign breadcrumb = "Test:one|two|three" | split: "|" %}
{{breadcrumb}}
{% include breadcrumb.md %}

{% include card.md %}
