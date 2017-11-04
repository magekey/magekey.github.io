---
layout: component
title: Product Sticker / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.product_sticker %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Product Sticker</li>
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
            The Product Sticker extension adds promotion stickers to products.
            With the extension, an administrator can manage stickers and assign to products and categories.
            </p>

            <p>
            Every sticker consist of label, width, height and sticker image.
            Extension allows you to create your own design and specify the background and text color for your sticker.
            To display sticker on frontend you should assign it to rules.
            The Product Sticker provides two types of rules:
            <ul>
                <li>Catalog Product - assign sticker to product</li>
                <li>Catalog Category  assign sticker to category</li>
            </ul>
            Using Display date fields in the rule you can simply setup the date and time when the sticker would be shown on the frontend.
            </p>

            <p>
            The Product Sticker extension provides another easy way to apply stickers.
            You can assign your stickers to product on Product Edit page in admin.
            The same with category entity. You can assign your stickers to category on Category Edit page.
            </p>

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
                    <li><a href="#stickers" class="toc-left">Sickers</a><a href="#stickers" class="toc-right">4</a></li>
                    <li><a href="#rules" class="toc-left">Rules</a><a href="#rules" class="toc-right">5</a></li>
                    <li><a href="#product-assign" class="toc-left">Assign Rule To Product</a><a href="#product-assign" class="toc-right">6</a></li>
                    <li><a href="#category-assign" class="toc-left">Assign Rule To Category</a><a href="#category-assign" class="toc-right">7</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p>
            The Product Sticker extension adds promotion stickers to products.
            With the extension, an administrator can manage stickers and assign to products and categories.
            </p>

            <p>The Product Sticker introduces its sections under <strong>Products > Product Stickers</strong> menu. The extension comes with 2 sections:</p>
            <ul>
                <li><strong>Stickers</strong> - allows administrator to manage stickers</li>
                <li><strong>Rules</strong> - allows administrator to manage rules</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide10.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="stickers"></a>
            <h2>Stickers</h2>

            <p>To create a new sticker navigate to <strong>Products > Product Stickers > Stickers</strong> section.</p>

            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide13.png" />
            </p>

            <p>To create a new sticker click <strong>Add Sticker</strong> button.</p>

            <p>The New Sticker screen is represented with three settings blocks: General Information, Sticker Design and Sticker Rules</p>

            <h3><i>General Information</i></h3>

            <ul>
                <li><strong>Sticker Label</strong> - defines the label of the sticker.</li>
                <li><strong>Is Active</strong> - enable/disable the sticker</li>
            </ul>

            <h3><i>Sticker Design</i></h3>

            <ul>
                <li><strong>Sticker Width</strong> - defines the width of the sticker.</li>
                <li><strong>Sticker Height</strong> - defines the height of the sticker.</li>
                <li><strong>Custom Design</strong> - enable/disable custom design.</li>
                <li><strong>Image</strong>(Custom Design disabled) - defines the image of the sticker.</li>
                <li><strong>Text Color</strong>(Custom Design enabled) - defines the text color of the sticker.</li>
                <li><strong>Background</strong>(Custom Design enabled) - defines the background color of the sticker.</li>
            </ul>

            <h3><i>Sticker Rules</i></h3>

            <ul>
                <li><strong>Rules</strong> - defines rules of the sticker.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 400px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide14.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="rules"></a>
            <h2>Rules</h2>

            <p>To create a new rule navigate to <strong>Products > Product Stickers > Rules</strong> section.</p>

            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide16.png" />
            </p>

            <p>To create a new sticker click <strong>Add Sticker</strong> button.</p>

            <p>The Rules screen is represented with two setting blocks: General Information and Assign Stickers.</p>

            <h3><i>General Information</i></h3>

            <ul>
                <li><strong>Rule Name</strong> - defines the name of the rule.</li>
                <li><strong>Rule Type</strong> - defines the type of the rule.</li>
                <li><strong>Product</strong>(Catalog Product Type) - defines the product of the rule.</li>
                <li><strong>Category</strong>(Catalog Category Type) - defines the category of the rule.</li>
                <li><strong>Display From</strong> - defines the start of the date display of the rule.</li>
                <li><strong>Display To</strong> - defines the end of the date display of the rule.</li>
            </ul>

            <h3><i>Assign Stickers</i></h3>

            <ul>
                <li><strong>Stickers</strong> - defines stickers of the rule.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px; max-height: 400px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide17.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="product-assign"></a>
            <h2>Assign Rule To Product</h2>

            <p>
            The Product Sticker extension provides another easy way to apply stickers.
            You can assign your stickers to product on Product Edit page in admin.
            </p>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide11.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="category-assign"></a>
            <h2>Assign Rule To Category</h2>

            <p>
            The Product Sticker extension provides another easy way to apply stickers.
            You can assign your stickers to category on Category Edit page in admin.
            </p>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/product-sticker/slide12.png" />
            </p>

        </div>
    </div>

</div>
