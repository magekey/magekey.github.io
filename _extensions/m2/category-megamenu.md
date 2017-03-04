---
layout: component
title: Category Mega Menu / Magento 2 / Extensions / MageKey GitHub
---
{% assign item = site.data.extensions.m2.category_megamenu %}

<ol class="breadcrumb">
    <li><a href="/">Home</a></li>
    <li><a href="/extensions">Extensions</a></li>
    <li><a href="/extensions/m2">Magento 2</a></li>
    <li class="active">Category Mega Menu</li>
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
            Category Mega Menu extension is an extension which helps store owners to improve default navigation menu.
            The main goal of the extension is to provide an easy solution to improve navigation.
            When using the Category Mega Menu you do not need to worry about creating the new menu or menu items.
            The extension uses the default Magento Catalog categories to display the navigation menu.
            The Category Mega Menu extension allows to display the category image and description in sub menu.
            </p>

            <p>
            The Category Mega Menu extension has a great design tool which helps your administrator to setup the menu design.
            The design tool allows you to switch the menu and sub menu size and backgrounds, update fonts and colors of your links,
            pick settings for hover and active links, adds borders and offets.
            </p>

            <p>
            The Category Mega Menu extension is fully responsive.
            </p>

            <h2>Category Mega Menu Features:</h2>

            <ul>
                <li>displaying Catalog categories in navigation menu</li>
                <li>displaying an image and description in sub menu</li>
                <li>implemented desing tool helps you to improve menu styles</li>
                <li>fully responsive</li>
            </ul>

            <h2>Design Features:</h2>

            <ul>
                <li>using design tool you can change the menu size and background.</li>
                <li>using design tool you can change sub menu background.</li>
                <li>using design tool you can change colors and fonts of you links, adds border and offsets.</li>
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
            Category Mega Menu extension is an extension which helps store owners to improve default navigation menu.
            The main goal of the extension is to provide an easy solution to improve navigation.
            When using the Category Mega Menu you do not need to worry about creating the new menu or menu items.
            The extension uses the default Magento Catalog categories to display the navigation menu.
            The Category Mega Menu extension allows to display the category image and description in sub menu.
            </p>

            <p style="margin-bottom: 5px;">
            The Category Mega Menu extension has a great design tool which helps your administrator to setup the menu design.
            The design tool allows you to switch the menu and sub menu size and backgrounds, update fonts and colors of your links,
            pick settings for hover and active links, adds borders and offets.
            </p>

            <p style="margin-bottom: 5px;">
            The Category Mega Menu extension is fully responsive.
            </p>

            <p style="margin-top: 10px;">Category Mega Menu introduces a configuration section under <strong>Content > Category Mega Menu</strong> menu. The extension comes with 1 section: <b>Configuration</b></p>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/category-megamenu/slide5.jpg" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <br/>
            <p>To set up the Category Mega Menu extension navigate to <strong>Content > Category Mega Menu > Configuration</strong> section.</p>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/category-megamenu/slide6.jpg" />
            </p>

            <p>The Configuration screen is represented with two settings blocks: Containers and Links.</p>

            <h3><i>Containers</i></h3>

            <ul>
                <li><strong>Top Menu</strong> - allows to change top menu block design.</li>
                <li><strong>Sub Menu</strong> - allows to change sub menu block design.</li>
                <li><strong>Sub Menu Sidebar</strong> - allows to change sidebar design in sub menu container.</li>
                <li><strong>Sub Menu Sidebar Text</strong> - allows to change text block design in sub menu container.</li>
            </ul>

            <br/>
            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/category-megamenu/slide7.jpg" />
            </p>

            <div class="pagebreak"></div>

            <h3><i>Links</i></h3>

            <ul>
                <li><strong>Top Links</strong>
                    <ul>
                        <li><strong>Default State</strong> - allows to change top link design for default state.</li>
                        <li><strong>Hover State</strong> - allows to change top link design for hover state.</li>
                        <li><strong>Active State</strong> - allows to change top link design for active state.</li>
                    </ul>
                </li>

                <li><strong>Sub Links (Level 1)</strong>
                    <ul>
                        <li><strong>Default State</strong> - allows to change sub link (Level 1) design for default state.</li>
                        <li><strong>Hover State</strong> - allows to change top link (Level 1) design for hover state.</li>
                        <li><strong>Active State</strong> - allows to change top link (Level 1) design for active state.</li>
                    </ul>
                </li>

                <li><strong>Sub Links (Level 2)</strong>
                    <ul>
                        <li><strong>Default State</strong> - allows to change sub link (Level 2) design for default state.</li>
                        <li><strong>Hover State</strong> - allows to change top link (Level 2) design for hover state.</li>
                        <li><strong>Active State</strong> - allows to change top link (Level 2) design for active state.</li>
                    </ul>
                </li>
            </ul>

            <br/>

            <p class="text-center">
                <img style="max-height: 700px" src="http://cdn.magekey.com/marketplace/extensions/m2/category-megamenu/slide8.jpg" />
            </p>

        </div>
    </div>

</div>
