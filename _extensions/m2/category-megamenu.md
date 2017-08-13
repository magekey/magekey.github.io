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
            Category Mega Menu is an extension intended for shop owners that will help you improve navigation menu.
            It uses standard Magento categories for displaying navigation menu, so you don't have to worry about making a new menu for your shop.
            The extension replaces a standard navigation menu with a new improved Mega Menu.
            It also supplements the menu with an information block located in the sub menu.
            The information block contains Category Image and Category description.
            It enables providing a customer with a more detailed information about an item in the category.
            </p>

            <p>
            With the Category Mega Menu extension, an administrator can customize your navigation menu design.
            For this purpose, a convenient design tool is implemented, which allows detailed customization of your menu styles.
            Using this tool, you can change the background for top menu and sub menu, add offsets and border, and specify size of your menu.
            You can customize font and size of the menu links, using both your browser standard fonts, and Google fonts,
            and to make different settings for hover links and active links states.
            You can also customize your information block design, and specify the text background and font.
            </p>

            <p>
            The Category Mega Menu extension is fully responsive.
            </p>

            <h2>Features:</h2>

            <ul>
                <li>using standard Magento categories for displaying navigation menu.</li>
                <li>using information block in sub menu, displaying Category Image and Category Description.</li>
                <li>with design tool an administrator can customize your menu design.</li>
                <li>fully responsive.</li>
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
            Category Mega Menu is an extension intended for shop owners that will help you improve navigation menu.
            It uses standard Magento categories for displaying navigation menu, so you don't have to worry about making a new menu for your shop.
            The extension replaces a standard navigation menu with a new improved Mega Menu.
            It also supplements the menu with an information block located in the sub menu.
            The information block contains Category Image and Category description.
            It enables providing a customer with a more detailed information about an item in the category.
            </p>

            <p style="margin-bottom: 5px;">
            The Category Mega Menu extension is fully responsive.
            </p>

            <br/>

            <p style="margin-top: 10px;">Category Mega Menu introduces a configuration section under <strong>Content > Category Mega Menu</strong> menu. The extension comes with 1 section: <b>Configuration</b></p>

            <p class="text-center">
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/category-megamenu/slide5.jpg" />
            </p>

            <div class="pagebreak"></div>

            <a name="configuration"></a>
            <h2>Configuration</h2>

            <br/>
            <p>To set up the Category Mega Menu extension navigate to <strong>Content > Category Mega Menu > Configuration</strong> section.</p>

            <p class="text-center">
                <img src="{{ site.data.config.mediaBaseUrl }}m2/category-megamenu/slide6.jpg" />
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
                <img src="{{ site.data.config.mediaBaseUrl }}m2/category-megamenu/slide7.jpg" />
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
                <img style="max-height: 700px" src="{{ site.data.config.mediaBaseUrl }}m2/category-megamenu/slide8.jpg" />
            </p>

        </div>
    </div>

</div>
