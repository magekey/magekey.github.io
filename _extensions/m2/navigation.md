---
layout: component
title: Navigation / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.navigation %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Navigation</li>
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
            Navigation Menu is an extension intended for shop owners that will help you improve navigation menu.
            The module allows you to create a hierarchical menu, use magento standard categories as links.
            As a link, you can also choose a product, a cms page, or specify a link manually.
            </p>

            <p>
            The Navigation Menu module provides a lot of features. You can set and customize the icon for your menu item or upload your own picture.
            Using default wysiwyg editor you can add your custom content in the sub menu.
            The extension allows you to specify a feature product which will be display on your sub menu.
            </p>

            <p>
            The Navigation Menu module provides a menu builder. You can quickly generate your menu using default magento categories or cms pages.
            </p>

            <p>
            You can use the Navigation Menu extension as a widget in any place of your website. It allows you to choose a template that will be displayed on the frontend.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>use navigation as a top menu and customize a top menu template.</li>
                <li>use category / product / cms page as a link of your item.</li>
                <li>setup top menu navigation and top menu template in design configuration.</li>
                <li>allows to setup icon or image for your manu item.</li>
                <li>use wysiwyg editor to add custom content to your sub menu.</li>
                <li>allows you to specify a feature product.</li>
                <li>quickly generate items based on categories or cms pages.</li>
                <li>use navigation as a widget.</li>
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
                    <li><a href="#navigation" class="toc-left">Manage Navigation</a><a href="#navigation" class="toc-right">4</a></li>
                    <li><a href="#topmenu" class="toc-left">Assign to Top Menu</a><a href="#topmenu" class="toc-right">5</a></li>
                    <li><a href="#items" class="toc-left">Manage Items</a><a href="#items" class="toc-right">6</a></li>
                    <li><a href="#generate" class="toc-left">Generate Items</a><a href="#generate" class="toc-right">7</a></li>
                    <li><a href="#update_item" class="toc-left">Update Item</a><a href="#update_item" class="toc-right">8</a></li>
                    <li><a href="#topmenu" class="toc-left">Setup top menu navigation</a><a href="#topmenu" class="toc-right">11</a></li>
                    <li><a href="#widget" class="toc-left">Create navigation widget</a><a href="#widget" class="toc-right">12</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p style="margin-bottom: 5px;">
            Navigation Menu is an extension intended for shop owners that will help you improve navigation menu.
            </p>

            <br/>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide1.png" />
            </p>

            <br/>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/navigation/front2.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="navigation"></a>
            <h2>Manage Navigation</h2>

            <br/>
            <p>Navigate to <strong>Content > Elements > Navigation</strong> section.</p>
            <br/>
            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide2.png" />
            </p>

            <br/>
            <h3>Create Navigation</h3>

            <p>To create a new navigation click <strong>Add Navigation</strong> button.</p>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide3.png" />
            </p>

            <p>The New Navigation screen is represented with one setting block: General Settings.</p>

            <h3><i>General Settings</i></h3>

            <ul>
                <li><strong>Navigation Name</strong> - defines the name of the navigation.</li>
                <li><strong>Store View</strong> - defines stores your navigation will be applied.</li>
            </ul>

            <br/>
            <p>Click <strong>Create</strong> button to create a new navigation and move to manage items section.</p>

            <br/>
            <div class="pagebreak"></div>

            <a name="topmenu"></a>
            <h2>Assign to Top Menu</h2>

            <br/>

            <p>This section allows us to assign a current navigation to the top menu.</p>
            <br/>
            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide15.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="items"></a>
            <h2>Manage Items</h2>

            <p>Navigate to Manage Items section.</p>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide4.png" />
            </p>

            <p>The Manage Items screen is represented with two columns: Tree on the left side and Item Form on the right side.</p>

            <h3><i>Tree column.</i></h3>

            <ul>
                <li><strong>Generate Items</strong> - generate new menu items based on default data.</li>
                <li><strong>Delete Items</strong> - delete all items for current navigation.</li>
            </ul>

            <ul>
                <li><strong>Add Root Item</strong> - add root item to menu.</li>
                <li><strong>Add Subitem</strong> - add subitem to the current selected item.</li>
            </ul>

            <div class="pagebreak"></div>

            <a name="generate"></a>
            <h2>Generate Items</h2>

            <p>Click <strong>Generate Items</strong> button to generate a new items based on magento data.</p>

            <h3>General</h3>

            <ul>
                <li><strong>Builder Entity</strong> - entity source data. Category and Page are available.</li>
                <li><strong>Delete existing items</strong> - delete all items of the current navigation before generate new items.</li>
            </ul>

            <br/>

            <p>Select entity as <strong>Category</strong> to generate items based on parent category.</p>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide5.png" />
            </p>

            <br/>

            <p>Select entity as <strong>Page</strong> to generate items based on cms pages.</p>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide6.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="update_item"></a>
            <h2>Update Item</h2>

            <p>The Item Form display on the right side when your menu item is selected.</p>

            <br/>

            <p class="text-center">
                <img style="max-height: 500px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide7.png" />
            </p>

            <br/>

            <h3>General Information</h3>

            <ul>
                <li><strong>Title</strong> - defines item title.</li>
                <li><strong>Active</strong> - enable/disable item.</li>
                <li><strong>Type</strong> - difines item type. Category, Product, Page ot Custom Url ara available.</li>
            </ul>

            <div class="pagebreak"></div>

            <h3>Icon</h3>

            <p>The Icon section provides two types: IcoMoon and Image.</p>

            <h3><i>Image</i></h3>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide8.png" />
            </p>

            <ul>
                <li><strong>Icon Image</strong> - upload image for your item icon.</li>
                <li><strong>Image Width</strong> - defines item icon image width.</li>
                <li><strong>Image Height</strong> - defines item icon image height.</li>
            </ul>

            <br/>

            <h3><i>IcoMoon</i></h3>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide9.png" />
            </p>

            <ul>
                <li><strong>Icon</strong> - defines icon from IcoMoon list.</li>
            </ul>

            <div class="pagebreak"></div>

            <h3><i>Sub Menu - Content</i></h3>

            <p>The content section provides two fields: Content Before and Content After.</p>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide10.png" />
            </p>

            <ul>
                <li><strong>Content Before</strong> - defines content before items in submenu.</li>
                <li><strong>Content After</strong> - defines content after items in submenu.</li>
            </ul>

            <br/>
            <h3><i>Sub Menu - Feature Product</i></h3>

            <p>The feature product section allows to assign a catalog product to your sub menu.</p>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide11.png" />
            </p>

            <ul>
                <li><strong>Product</strong> - defines feature product.</li>
            </ul>

            <div class="pagebreak"></div>

            <a name="topmenu"></a>
            <h2>Setup top menu navigation</h2>

            <br/>

            <p>To setup top menu navigate to <strong>Content > Design > Configuration</strong>. Select a theme you want to change.</p>

            <p>Move to Navigation section and choose a Top Menu.</p>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide12.png" />
            </p>

            <br/>

            <ul>
                <li><strong>Top Menu</strong> - defines navigation for top menu.</li>
                <li><strong>Top Menu Title</strong> - defines title of the navigation.</li>
                <li><strong>Top Menu Template</strong> - defines template of the navigation.</li>
            </ul>

            <div class="pagebreak"></div>

            <a name="widget"></a>
            <h2>Create navigation widget</h2>

            <br/>

            <p>To create a new navigation widget switch to <strong>Content > Elements > Widgets</strong> and click <strong>Add Widget</strong> button.</p>
            <p>Select Type field as "Navigation" and choose a theme.</p>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide13.png" />
            </p>

            <p>Click <strong>Continue</strong> button to create a new widget.</p>

            <p>Update Storefront Properties tab and setup layout. Move to <strong>Widget Options</strong> tab and choose navigation menu.</p>

            <p class="text-center">
                <img style="max-height: 300px" src="{{ site.data.config.mediaBaseUrl }}m2/navigation/slide14.png" />
            </p>

        </div>
    </div>

</div>
