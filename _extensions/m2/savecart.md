---
layout: component
title: Save Shopping Cart / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.savecart %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Save Shopping Cart</li>
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
            The Save Shopping Cart extension will allow your customers to save their shopping carts for later or to duplicate previous orders.
            Add products to the shopping cart and select the "Save Shopping Cart" button.
            Customer will be able to save shopping cart on Minicart popup or on Shopping Cart page.
            Customers can save multiple carts.
            Carts can be viewed and accessed from the "Customer Accounts" page by selecting the "Saved Shopping Carts" link in the "My Account" navigation.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>two-step process for saving carts.</li>
                <li>customers can save multiple carts.</li>
                <li>with design tool an administrator can customize your menu design.</li>
                <li>carts can be restored until customer is logged in.</li>
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
                    <li><a href="#save-shopping-cart" class="toc-left">Save Shopping Cart</a><a href="#save-shopping-cart" class="toc-right">5</a></li>
                    <li><a href="#restore-shopping-cart" class="toc-left">Restore Shopping Cart</a><a href="#restore-shopping-cart" class="toc-right">6</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p>
            The Save Shopping Cart extension will allow your customers to save their shopping carts for later or to duplicate previous orders.
            Add products to the shopping cart and select the "Save Shopping Cart" button.
            Customer will be able to save shopping cart on Minicart popup or on Shopping Cart page.
            Customers can save multiple carts.
            Carts can be viewed and accessed from the "Customer Accounts" page by selecting the "Saved Shopping Carts" link in the "My Account" navigation.
            </p>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide1.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <p style="margin-top: 10px;">Save Shopping Cart introduces a configuration section under <strong>Stores > Configuration > Advanced Tab > Advanced</strong> menu.</p>

            <p>The Configuration screen is represented with one setting block. To disable Save Shopping cart extension use <b>{{ item.code }}</b> field and choose <b>Disable</b></p>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide6.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="save-shopping-cart"></a>
            <h2>Save Shopping Cart</h2>

            <p style="margin-top: 10px;">Save Shopping Cart extension introduces two ways to saving cart.</p>

            <h3>Save shopping cart on Minicart popup</h3>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; width: 200px; margin-right: 5%;" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide2.png" />
                <img style="max-height: 700px; width: 600px;" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide3.png" />
            </p>

            <br/>

            <h3>Save shopping cart on Shopping cart page</h3>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; max-height: 600px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide4.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="restore-shopping-cart"></a>
            <h2>Restore Shopping Cart</h2>

            <h3>Restore saved shopping cart on "Saved Shopping Carts" page in "My Account" navigation</h3>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; max-height: 600px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide1.png" />
            </p>

        </div>
    </div>

</div>
