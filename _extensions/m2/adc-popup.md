---
layout: component
title: Added to Cart Popup / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.adcpopup %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Added to Cart Popup</li>
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
            Added to Cart Popup is an extension intended for shop owners that will help you to improve adding to shopping cart process.
            Every time when customer adds new product to his shopping cart the popup will be shown on frontend.
            The extension works correctly with all product types.
            <p>
            </p>
            The popup consist of two sections: left and right. On the left section will be shown the product your customer just added to cart.
            On the bottom of popup window shows up product list which could be interested to your customer. This section can be setup in admin. You can define categories you would like to shows up in popup.
            </p>
            <p>
            On the right section shows up a shopping cart summary. In this section customer can continue shopping or jump to checkout page.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>shows up popup when product added to cart</li>
                <li>works with all product types</li>
                <li>shows up product list from related categories.</li>
                <li>shopping cart summary section</li>
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
                    <li><a href="#configuration" class="toc-left">Configuration</a><a href="#configuration" class="toc-right">4</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p style="margin-bottom: 5px;">
            Added to Cart Popup is an extension intended for shop owners that will help you to improve adding to shopping cart process.
            Every time when customer adds new product to his shopping cart the popup will be shown on frontend.
            The extension works correctly with all product types.
            </p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/adc-popup/slide1.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <br/>
            <p>To set up the Added to Cart Popup extension navigate to <strong>Stores > Configuration > Sales tab > Added to Cart Popup</strong> section.</p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/adc-popup/slide2.png" />
            </p>

            <p>The Configuration screen is represented with two settings blocks: General and Product List.</p>

            <h3><i>General</i></h3>

            <ul>
                <li><strong>Enabled</strong> - enable/disable the extension.</li>
            </ul>

            <h3><i>Product List</i></h3>

            <ul>
                <li><strong>Enabled</strong> - enable/disable product list in popup.</li>
                <li><strong>Fetch products from</strong> - allows to setup categories which would be use to shows up related products.</li>
                <li><strong>Products Count</strong> - count of product which will be shown in product list</li>
            </ul>

        </div>
    </div>

</div>
