---
layout: extensions
title: Extensions / MageKey GitHub
---
<div class="row">
    {% for ext in site.data.extensions %}
    {% assign item = ext[1] %}

    {% include list.md %}

    {% endfor %}
</div>
