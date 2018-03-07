---
layout: component
title: Stores Flags / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.stores_flags %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Stores Flags</li>
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
            Stores Flags is an extension that adds country flags to Store View.
            The extension use own "choose store" template and shows up country flags in drop down instead of simple text.
            </p>
            <p>
            You can simply add a country flag to your store in admin.
            Administrator can manage extension settings and enable or disable it on frontend.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>new "choose store" template on frontend.</li>
                <li>ability to enable/disable store flags in admin settings</li>
                <li>ability to enable/disable compiled styles in admin settings</li>
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
                    <li><a href="#guide" class="toc-left">Setup Store Flag</a><a href="#guide" class="toc-right">3</a></li>
                    <li><a href="#configuration" class="toc-left">Configuration</a><a href="#configuration" class="toc-right">4</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p style="margin-bottom: 5px;">
            Stores Flags is an extension that adds country flags to Store View.
            The extension use own "choose store" template and shows up country flags in drop down instead of simple text.
            </p>

            <br/>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/stores-flags/slide1.png" />
            </p>

            <br/><br/>

            <a name="guide"></a>
            <h2>Setup Store Flag</h2>

            <br/>
            <p>To set up a flag to your store navigate to <strong>Stores > All Stores</strong> menu.</p>
            <p>Select Store View you need to update. On store view edit page choose Store Country in Store View Flag section</p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/stores-flags/slide2.png" />
            </p>

            <p>Click Save Store View to update store view settings.</p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <br/>
            <p>To change Stores Flags extension settings navigate to <strong>Stores > Configuration > General tab > Stores Flags</strong> section.</p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/stores-flags/slide3.png" />
            </p>

            <p>The Configuration screen is represented with the one setting block: General.</p>

            <h3><i>General</i></h3>

            <ul>
                <li><strong>Enabled</strong> - enable/disable the extension.</li>
                <li><strong>Use Compiled Styles</strong> - if this option is enabled the compiled css styles will be added to the head of your page on the frontend.</li>
            </ul>

        </div>
    </div>

</div>
