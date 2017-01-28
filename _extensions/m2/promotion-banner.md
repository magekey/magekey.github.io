---
layout: component
title: Promotion Banner / Magento 2 / Extensions / MageKey GitHub
breadcrumb: Promotion Banner
---
{% assign item = site.data.extensions.m2.promotion_banner %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">{{ page.breadcrumb }}</li>
</ol>

{% include card.md %}

<div class="details">

    <ul class="nav nav-tabs" role="tablist">
        <li role="presentation" class="active"><a href="#description" aria-controls="description" role="tab" data-toggle="tab">Description</a></li>
        <li role="presentation"><a href="#install_guide" aria-controls="install_guide" role="tab" data-toggle="tab">Installation Guide</a></li>
        <li role="presentation"><a href="#user_guide" aria-controls="user_guide" role="tab" data-toggle="tab">User Guide</a></li>
    </ul>

    <div class="tab-content">

        <!-- Description -->
        <div role="tabpanel" class="tab-pane active" id="description" aria-expanded="true">

            <div class="pagebreak"></div>

            Coming Soon

        </div>

        <!-- Installation Guide -->
        <div role="tabpanel" class="tab-pane" id="install_guide">

            <div class="pagebreak"></div>

            {% include install_guide.md %}

        </div>

        <!-- User Guide -->
        <div role="tabpanel" class="tab-pane" id="user_guide">

            <div class="pagebreak"></div>

            Coming Soon

        </div>
    </div>

</div>
