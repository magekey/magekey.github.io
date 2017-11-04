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
            Save Shopping Cart extension will allow your customers to save their shopping carts for later or to duplicate previous orders.
            </p>
            <p>
            Add products to the shopping cart and select the "Save Shopping Cart" button.
            </p>
            <p>
            Save Shopping Cart extension introduces two ways to saving cart:
            <ul>
                <li>Save shopping cart on Minicart popup</li>
                <li>Save shopping cart on Shopping cart page</li>
            </ul>
            </p>
            <p>
            Customers can save multiple carts.
            </p>
            <p>
            Carts can be viewed and accessed from the "Customer Accounts" page by selecting the "Saved Shopping Carts" link in the "My Account" navigation.
            </p>
            <p>Save Shopping Cart extension provides "Restore cart" button to apply your saved cart.</p>

            <p>Save Shopping Cart extension allows your administrator to manage saved carts. They can create new carts, create new order based on saved carts, send emails to customers and assign customers to cart.</p>

            <h2>Features:</h2>

            <ul>
                <li>two-step process for saving carts.</li>
                <li>customers can save cart as guests</li>
                <li>customers can save multiple carts.</li>
                <li>customers can share carts.</li>
                <li>cart email</li>
                <li>manage saved carts in admin.</li>
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
                    <li><a href="#save-shopping-cart" class="toc-left">Save Shopping Cart</a><a href="#save-shopping-cart" class="toc-right">4</a></li>
                    <li><a href="#restore-shopping-cart" class="toc-left">Restore Shopping Cart</a><a href="#restore-shopping-cart" class="toc-right">5</a></li>
                    <li><a href="#administration" class="toc-left">Administration</a><a href="#administration" class="toc-right">6</a></li>
                    <li><a href="#manage-carts" class="toc-left">Manage Carts</a><a href="#manage-carts" class="toc-right">7</a></li>
                    <li><a href="#view-cart" class="toc-left">View Cart</a><a href="#view-cart" class="toc-right">8</a></li>
                    <li><a href="#configuration" class="toc-left">Configuration</a><a href="#configuration" class="toc-right">9</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p>
            The Save Shopping Cart extension will allow your customers to save their shopping carts for later or to duplicate previous orders.
            Add products to the shopping cart and select the "Save Shopping Cart" button.
            Customer will be able to save shopping cart on Minicart popup or on Shopping Cart page.
            </p>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide1.png" />
            </p>

            <p>
            Carts can be viewed and accessed from the "Customer Accounts" page by selecting the "Saved Shopping Carts" link in the "My Account" navigation.
            </p>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide5.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="save-shopping-cart"></a>
            <h2>Save Shopping Cart</h2>

            <p style="margin-top: 10px;">Save Shopping Cart extension introduces two ways to saving cart.</p>

            <h3>Save shopping cart on Minicart popup</h3>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; margin-right: 5%;" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide1.png" />
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

            <h3>Restore saved shopping cart on "My Saved Carts" page in "My Account" navigation</h3>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; max-height: 600px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide6.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="administration"></a>
            <h2>Administration</h2>

            <p>Save Shopping Cart introduces its sections under <strong>Sales > Save Cart</strong> menu. The extension comes with 2 sections:</p>
            <ul>
                <li><strong>View Carts</strong> - allows administrator to manage saved cart</li>
                <li><strong>Configuration</strong> - allows administrator to setup the module</li>
            </ul>

            <br/>
            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide10.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="manage-carts"></a>
            <h2>Manage Carts</h2>

            <p>Navigate to <strong>Sales > Save Cart > View Carts</strong> section.</p>

            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide12.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="view-cart"></a>
            <h2>View Cart</h2>

            <p>The Saved Cart screen is represented with two settings blocks: General Information and Cart Items</p>

            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide13.png" />
            </p>

            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide14.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <p style="margin-top: 10px;">Save Shopping Cart introduces a configuration section under <strong>Sales > Save Cart > Configuration</strong> menu.</p>

            <p>The Configuration screen is represented with three settings blocks: General, Guest Settings and Email Notification</p>

            <h3><i>General</i></h3>

            <ul>
                <li><strong>Enabled</strong> - enable/disable the module on frontend</li>
            </ul>

            <h3><i>Guest Settings</i></h3>

            <ul>
                <li><strong>Allow shared cart link</strong> - enable/disable ability to use cart shared link</li>
            </ul>

            <h3><i>Email Notification</i></h3>

            <ul>
                <li><strong>Email Sender</strong> - defines email "from" address</li>
                <li><strong>Email Template</strong> - defines email template</li>
                <li><strong>Send Email Copy To</strong> - defines bcc emails</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/savecart/slide11.png" />
            </p>

        </div>
    </div>

</div>
