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
        <li role="presentation" class="active"><a href="#overview" aria-controls="overview" role="tab" data-toggle="tab">Overview</a></li>
        <li role="presentation"><a href="#install_guide" aria-controls="install_guide" role="tab" data-toggle="tab">Installation Guide</a></li>
        <li role="presentation"><a href="#user_guide" aria-controls="user_guide" role="tab" data-toggle="tab">User Guide</a></li>
    </ul>

    <div class="tab-content">

        <!-- Overview -->
        <div role="tabpanel" class="tab-pane active" id="overview" aria-expanded="true">
            <div class="pagebreak"></div>

            <p>
            The extension creates banner groups and allows you to place it on any page using Magento widgets.
            Each group can contain several banners.
            The Banner settings allow show up banner at any date or time.
            Promotion Banner Slider extension provides Promotion block settings; it allow to place your notes over banner.
            </p>

            <p>
            When using Promotion Banner, the first step is to create a banner groups. This group will be used to place bundle of your banners on page.
            The next step is to create your banners by selecting group, date and time, by adding image, and by updating promotion block banner settings.
            Once banners are created place your banner groups on any page through the Magento widgets.
            </p>

            <h2>Feature highlights</h2>

            <h3>Manage Groups</h3>

            <p>The extension allows to create banner groups and place this group on any page using Magento widgets.</p>

            <h3>Create a banner</h3>

            <p>The extension allows to create multiple banners and assign them to group.</p>

            <h3>Banner date and time</h3>

            <p>Administrator has control over when each banner is displayed and choose date and time.</p>

            <h3>Banner promotion block</h3>

            <p>Administrator may setup promotion block over banner.</p>

        </div>

        <!-- Installation Guide -->
        <div role="tabpanel" class="tab-pane" id="install_guide">

            <div class="pagebreak"></div>

            {% include install_guide.md %}

        </div>

        <!-- User Guide -->
        <div role="tabpanel" class="tab-pane" id="user_guide">

            <div class="pagebreak"></div>

            <div class="toc-block">
                <h3>Table of contents:</h3>
                <ul class="toc">
                    <li><a href="#toc-overview" class="toc-left">Overview</a><a href="#toc-overview" class="toc-right">3</a></li>
                    <li><a href="#managing-groups" class="toc-left">Managing Groups</a><a href="#managing-groups" class="toc-right">4</a></li>
                    <li><a href="#managing-banners" class="toc-left">Managing Banners</a><a href="#managing-banners" class="toc-right">5</a></li>
                </ul>
            </div>

            <div class="pagebreak"></div>

            <a name="toc-overview"></a>
            <h2>Overview</h2>

            <p>
            The extension creates banner groups and allows you to place it on any page using Magento widgets.
            Each group can contain several banners.
            The Banner settings allow show up banner at any date or time.
            Promotion Banner Slider extension provides Promotion block settings; it allow to place your notes over banner.
            </p>

            <p>Promotion Banner introduces its sections under <strong>Content > Promotion Banner</strong> menu. The extension comes with 2 sections:</p>
            <ul>
                <li><strong>Manage Groups</strong> - allows administrator to create banner groups</li>
                <li><strong>Manage Banners</strong> - allows administrator to create banners</li>
            </ul>

            <p>&nbsp;</p>
            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-menu.png" />
            </p>

            <div class="pagebreak"></div>

            <a name="managing-groups"></a>
            <h2>Managing Groups</h2>

            <p>To create a group navigate to <strong>Content > Promotion Banner > Manage Groups</strong> section.</p>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-group-grid.png" />
            </p>

            <p>To create a Group click <strong>Add New Group</strong> button.</p>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-group-edit.png" />
            </p>

            <p>The New Group screen is represented with one settings block: Group Information.</p>

            <h3><i>Group Information</i></h3>

            <p>This screen allows store administrator to name the Group. The following settings are available:</p>

            <ul>
                <li><strong>Group Name</strong> - defines the name of the banner group.</li>
            </ul>

            <div class="pagebreak"></div>

            <a name="managing-banners"></a>
            <h2>Managing Banners</h2>

            <p>To create a banner navigate to <strong>Content > Promotion Banner > Manage Banners</strong> section.</p>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-banner-grid.png" />
            </p>

            <p>To create a Banner click <strong>Add New Banner</strong> button.</p>

            <p>The New Banner screen is represented with four settings blocks: General, Date & Time, Banner, Promo.</p>

            <h3><i>General</i></h3>

            <ul>
                <li><strong>Active</strong> - allows enabling/disabling the Banner.</li>
                <li><strong>Group</strong> - defines the name of the group.</li>
                <li><strong>Banner Name</strong> - defines the name of the banner for internal purposes.</li>
            </ul>

            <br/>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-banner-edit-general.png" />
            </p>

            <h3><i>Date & Time</i></h3>

            <ul>
                <li><strong>Date Settings</strong>
                    <ul>
                        <li><strong>Use Date</strong> - enables/disable filter by dates</li>
                        <li><strong>Start Date</strong> - defines start date when banner will be displayed</li>
                        <li><strong>End Date</strong> - defines end date when banner will be displayed</li>
                    </ul>
                </li>

                <div class="pagebreak"></div>

                <li><strong>Time Settings</strong>
                    <ul>
                        <li><strong>Use Time</strong> - enables/disable filter by time</li>
                        <li><strong>Start Time</strong> - defines start time when banner will be displayed</li>
                        <li><strong>End Time</strong> - defines end date time banner will be displayed</li>
                    </ul>
                </li>
            </ul>

            <br/>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-banner-edit-datetime.png" />
            </p>

            <h3><i>Banner</i></h3>

            <ul>
                <li><strong>Banner Image</strong>
                    <ul>
                        <li><strong>Choose Image</strong> - defines image of the banner</li>
                    </ul>
                </li>
                <li><strong>Banner Settings</strong>
                    <ul>
                        <li><strong>URL</strong> - defines banner URL</li>
                        <li><strong>Width</strong> - defines width of the banner</li>
                        <li><strong>Height</strong> - defines height of the banner</li>
                    </ul>
                </li>
            </ul>

            <br/>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-banner-edit-banner.png" />
            </p>

            <div class="pagebreak"></div>

            <h3><i>Promo</i></h3>

            <ul>
                <li><strong>General</strong>
                    <ul>
                        <li><strong>Active</strong> - enables/disables promo block on banner</li>
                    </ul>
                </li>
                <li><strong>Promo Box Settings</strong>
                    <ul>
                        <li><strong>Width</strong> - defines width of the promo block</li>
                        <li><strong>Height</strong> - defines height of the promo block</li>
                        <li><strong>Position</strong> - defines position of the promo block. Available options: Top Left, Top Right, Bottom Left, Bottom Right</li>
                        <li><strong>Background</strong> - defines background color of the promo block</li>
                    </ul>
                </li>
                <li><strong>Button Settings</strong>
                    <ul>
                        <li><strong>Show Button</strong> - enables/disables button on the promo block</li>
                        <li><strong>Button Title</strong> - defines title of button on the promo block</li>
                        <li><strong>Button Title Color</strong> - defines title color of the button on the promo block</li>
                        <li><strong>Button Background</strong> - defines background color of the button on the promo block</li>
                    </ul>
                </li>
                <li><strong>Content</strong>
                    <ul>
                        <li><strong>Promo Content</strong> - defines content text on the promo block</li>
                    </ul>
                </li>
            </ul>

            <br/>

            <p class="text-center">
                <img src="http://cdn.magekey.com/marketplace/extensions/m2/promotion-banner/ug-banner-edit-promo.png" />
            </p>

        </div>
    </div>

</div>
