---
layout: extensions
title: Extensions / MageKey GitHub
---
<div class="row">
    {% for ext in site.data.extensions | inspect %}
    <div class="col-sm-6 col-md-4">
        <div class="thumbnail">
            <img src="{{ ext.url }}" alt="{{ ext.title }}">
            <div class="caption">
                <h3>Promotion Banner</h3>
                <p>Promotion Banner is simple extension to manage and show up banners at specific date and time.</p>
                <p class="text-center">
                    <a target="_blank" href="/extensions/promotion-banner.html" class="btn btn-primary" role="button">Promotion Banner</a>
                </p>
            </div>
        </div>
    </div>
    {% endfor %}
</div>
