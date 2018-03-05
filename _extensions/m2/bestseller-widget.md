---
layout: component
title: Bestseller Widget / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.bestseller_widget %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Bestseller Widget</li>
</ol>

{% include card.md %}

<div class="details">

    <ul class="nav nav-tabs" role="tablist">
        <li role="presentation" class="active"><a href="#overview" aria-controls="overview" role="tab" data-toggle="tab">Overview</a></li>
        <li role="presentation"><a href="#install_guide" aria-controls="install_guide" role="tab" data-toggle="tab">Installation Guide</a></li>
        <li role="presentation"><a href="#user_guide" aria-controls="user_guide" role="tab" data-toggle="tab">User Guide</a></li>
    </ul>

    <div class="tab-content">

        <!-- Overview -->
        <div role="tabpanel" class="tab-pane active" id="overview" aria-expanded="true">
            <div class="pagebreak"></div>

            <p>
            Bestseller Widget is an extension that adds new bestseller widget to frontend.
            Extension has a 3 types of the bestseller: weekly, monthly and yearly.
            </p>
            <p>
            You can add new bestseller widget through the default Magento widgets.
            The Bestseller Widget extension use tabs to show up multiple bestseller types in the one section.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>Bestseller Daily Widget</li>
                <li>Bestseller Monthly Widget</li>
                <li>Bestseller Yearly Widget</li>
                <li>tabs for multiple bestseller types</li>
            </ul>

        </div>

        <!-- Installation Guide -->

        <div role="tabpanel" class="tab-pane" id="install_guide">

            <div class="pagebreak"></div>

            {% include install_guide_cli.md %}

        </div>

        <!-- User Guide -->
        <div role="tabpanel" class="tab-pane" id="user_guide">

            <div class="pagebreak"></div>

            <div class="toc-block">
                <h3>Table of contents:</h3>
                <ul class="toc">
                    <li><a href="#toc-overview" class="toc-left">Overview</a><a href="#toc-overview" class="toc-right">3</a></li>
                    <li><a href="#configuration" class="toc-left">Add Bestseller Widget</a><a href="#guide" class="toc-right">3</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p style="margin-bottom: 5px;">
            Bestseller Widget is an extension that adds new bestseller widget to the frontend.
            Extension has a 3 types of the bestseller: weekly, monthly and yearly.
            </p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/bestseller-widget/slide1.png" />
            </p>

            <br/><br/>

            <a name="guide"></a>
            <h2>Add Bestseller Widget to frontend</h2>

            <br/>
            <p>To set up a new bestseller widget navigate to <strong>Content > Widgets</strong> menu.</p>
            <p>Add new widget, select type as <strong>Bestseller</strong> and choose a theme to place your bestseller widget.</p>
            <p>On the next page you should to update widget options and setup title and choose bestseller types you want to show up on the frontend.</p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/bestseller-widget/slide2.png" />
            </p>

            <p>Click Save and refresh Magento cache to render changes on the frontend.</p>

        </div>
    </div>

</div>
